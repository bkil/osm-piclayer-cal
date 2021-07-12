# Berekfürdő

## 2016-12

* módosítva 2020-01
* lépték M 1:4000

### Belterület

* vékonyabbak a vonalak, jobban láthatók egyes részletek

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

### Átfogó nézet külterülettel

* vastagabbak a vonalak, épületek körüli írás kevésbé olvasható

```
wget \
  -O "t-10.1m1 szabályozási terv - belterület.pdf" \
  "https://www.berekfurdo.hu/?module=news&action=getfile&aid=44021"

gs \
  -sDEVICE=jpeg \
  -r600 \
  -o "t-10.1m1 szabályozási terv - belterület.jpg" \
  "t-10.1m1 szabályozási terv - belterület.pdf"
  # 21600x14400
```
