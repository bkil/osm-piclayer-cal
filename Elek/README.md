# Elek

```
wget https://elek.hu/qb/qb_letoltes/letoltheto_anyagok/rend_terv_2015uj.zip

unzip \
  -j \
  rend_terv_2015uj.zip \
  "RendezВsi Terv - гj 2015/tervlapok/szabаlyozаs-belt-SZ2-ELEK-2000-Р-i szelv.pdf" \
  "RendezВsi Terv - гj 2015/tervlapok/szabаlyozаs-belt-SZ2-ELEK-2000 - D-i szelv.pdf"

gs \
  -sDEVICE=jpeg \
  -r150 \
  -o "szabаlyozаs-belt-SZ2-ELEK-2000-Р-i szelv.jpg" \
  "szabаlyozаs-belt-SZ2-ELEK-2000-Р-i szelv.pdf"
  # 10333x4967

gs \
  -sDEVICE=jpeg \
  -r150 \
  -o "szabаlyozаs-belt-SZ2-ELEK-2000 - D-i szelv.jpg" \
  "szabаlyozаs-belt-SZ2-ELEK-2000 - D-i szelv.pdf"
  # 10333x4967
```
