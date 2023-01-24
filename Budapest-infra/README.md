# Budapest infrastruktúra

```
wget \
  -nc \
  -O m.pdf \ "https://budapest.hu/telepulesrendezesitervek/TSZT/TSZT/TSZT%20hat%C3%A1lyos%202021.04.03.%20-/II_kotet_Alatamaszto/II_kotet_Alatamaszto_munkaresz.pdf" &&
for P in 239 241 249 256 259 296 304 311 323 326 329 332; do
  gs -sDEVICE=jpeg -r300 -sPageList=$P -o m-$P.jpeg m.pdf
done
# 2481x3508
# 4959x3506
```
