# Budapest XV. kerület, Pestújhely

```
wget \
  -nc \
  https://www.bpxv.hu/r4wf434rf/uploads/2015/09/SZAB_2E_SZELV_15.pdf \
  https://www.bpxv.hu/r4wf434rf/uploads/2015/09/SZAB_2E_SZELV_14.pdf \
  https://www.bpxv.hu/r4wf434rf/uploads/2015/09/SZAB_2E_SZELV_18.pdf \
  https://www.bpxv.hu/r4wf434rf/uploads/2015/09/SZAB_2E_SZELV_19.pdf

for F in *.pdf; do
  gs \
    -sDEVICE=jpeg \
    -r300 \
    -o "`basename "$F" .pdf`.jpg" \
    "$F"
done
# 10828x8975
```
