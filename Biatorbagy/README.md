# Biatorbágy

```
wget \
  http://biatorbagy.hu/system/files/4-200605.25.pdf \
  http://biatorbagy.hu/system/files/1_a_melleklet_bia_tszt_tervlap.pdf \
  http://biatorbagy.hu/system/files/1_b_mellkelet_bia_tszt_vedelmek_es_korlatozasok_tervlap.pdf

gs -sDEVICE=jpeg -r300 -o 1_b_mellkelet_bia_tszt_vedelmek_es_korlatozasok_tervlap.jpg 1_b_mellkelet_bia_tszt_vedelmek_es_korlatozasok_tervlap.pdf # 14042x9933
gs -sDEVICE=jpeg -r300 -o 1_a_melleklet_bia_tszt_tervlap.jpg 1_a_melleklet_bia_tszt_tervlap.pdf # 14042x9933
gs -sDEVICE=jpeg -r600 -sPageList=8,9 -o 4-200605.25-%d.jpg 4-200605.25.pdf # 4961x7016
```
