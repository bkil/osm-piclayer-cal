# Ecsed

* Házszámok, helyrajzi számok, épületek, utcanevek, övezetek, zöld területek, vizek, iparterületek

```
wget
  -nc \
  https://ecsed.hu/wp-content/uploads/2020/01/H%C3%89SZ-2.-mell._SZ_2-belterulet-szabalyozas-201910-al%C3%A1%C3%ADrt.pdf \
  https://ecsed.hu/wp-content/uploads/2020/01/H%C3%89SZ-1.-mell._SZ_1-kulter%C3%BClet-szabalyozas-201910-al%C3%A1%C3%ADrt.pdf

for F in *.pdf; do
  gs \
    -sDEVICE=jpeg \
    -r450 \
    -o "`basename "$F" .pdf`.jpg" \
    "$F"
done
# 21063x14900
# 14900x21063
```
