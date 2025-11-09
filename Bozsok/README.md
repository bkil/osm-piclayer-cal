# Bozsok

## Bozsok 2017

```
wget \
  "https://bozsok.hu/wp-content/uploads/2017/02/Bozsok-H%c3%89SZ-m%c3%b3d-Elfogadott2017_01_24.pdf" \
  -O Bozsok-HESZ.2017-01-24.pdf

gs \
  -sDEVICE=jpeg \
  -r300 \
  -sPageList=51-52 \
  -o "Bozsok-2017-%02d.jpg" \
  Bozsok-HESZ.2017-01-24.pdf
  # 3508x4961
```
