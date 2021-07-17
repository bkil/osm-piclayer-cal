# Doboz

## Helyi Építési Szabályzat

```
wget \
  "https://www.doboz.hu/system/files_force/4.%20sz.%20szab.%20szelveny.pdf?download=1" \
  "https://www.doboz.hu/system/files_force/8-m.%20sz.%20szelv%C3%A9ny-3%20v%C3%A9gleges.pdf?download=1" \
  "https://www.doboz.hu/system/files_force/9.%20sz.%20szab.%20szelveny.pdf?download=1"

for F in *.pdf; do
gs \
  -sDEVICE=jpeg \
  -r300 \
  -o "`basename "$F" .pdf`.jpg" \
  "$F"
  # 11104x7017
done
```

## Források

Van még sok másik szelvény is:

* https://www.doboz.hu/system/files_force/szab%C3%A1lyoz%C3%A1s%20szelv%C3%A9nyez%C3%A9s.pdf?download=1
* https://www.doboz.hu/content/helyi-%C3%A9p%C3%ADt%C3%A9si-szab%C3%A1lyzat
