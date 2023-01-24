# Budapest infrastruktúra

```
wget \
  -nc \
  -O m.pdf \ "https://budapest.hu/telepulesrendezesitervek/TSZT/TSZT/TSZT%20hat%C3%A1lyos%202021.04.03.%20-/II_kotet_Alatamaszto/II_kotet_Alatamaszto_munkaresz.pdf" &&
gs -sDEVICE=jpeg -r300 -sPageList=326 -o m-326.jpeg m.pdf
# 4959x3506
```
