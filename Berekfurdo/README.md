# Berekfürdő

```
wget https://www.t4terv.hu/download/782/ -O Berekfurdo.zip

unzip \
  -j \
  Berekfurdo.zip \
  "Egybeszerkesztett tervlapok Вs egysВges HРSZ/T-10.2m2 Szabаlyozаsi terv - KБlterБlet.pdf"

gs \
  -sDEVICE=jpeg \
  -r300 \
  -o "Berekfurdo.jpg" \
  "T-10.2m2 Szabаlyozаsi terv - KБlterБlet.pdf"
  # 10800x7200
```
