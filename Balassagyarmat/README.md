# Balassagyarmat

## 2022 TRT

```
wget \
  "https://balassagyarmat.hu/wp-content/uploads/hirdetmeny/telep%C3%BCl%C3%A9srendez%C3%A9si%20eszk%C3%B6z%C3%B6k%20fel%C3%BClvizsg%C3%A1lata%20tervek.zip"

unzip \
  -j \
  "településrendezési eszközök felülvizsgálata tervek.zip" \
  M2-BGYMT-HРSZ_SZT-4000_A2.pdf

gs \
  -sDEVICE=jpeg \
  -r300 \
  -sPageList=2-15 \
  -o "TRT-2022-%02d.jpg" \
  M2-BGYMT-HРSZ_SZT-4000_A2.pdf
  # 7017x4963
```
