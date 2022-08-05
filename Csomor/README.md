# Csömör

## HÉSZ 17/2019

* http://www.csomor.hu/dokumentumtar/425135/172019-vii18-sz-rendelet-a-helyi-epitesi-szabalyzatrol

```
wget \
  -nc \
  -O csomor_2019_hesz_szt1-10_mellekletek.pdf \
  http://www.csomor.hu/document/get/425136/csomor_2019_hesz_szt1-10_mellekletek.pdf &&

gs \
  -sDEVICE=jpeg \
  -r300 \
  -sPageList=3-12 \
  -o "2019_hesz-%02d.jpg" \
  "csomor_2019_hesz_szt1-10_mellekletek.pdf"
  # 14821x10796
```
