# Sátoraljaújhely

```
wget \
  http://www.satoraljaujhely.hu/files/letoltesek/telepulesiarculat/tortenelmi%20varosreszek/Tortenelmi%20varosreszek%20terkepi%20lehatarolasa.pdf \
  http://www.satoraljaujhely.hu/files/letoltesek/onkormanyzat/kozerdeku/Onk_kozzeteteli/integr_varosf_strat.pdf

gs \
  -sDEVICE=jpeg \
  -r600 \
  -o "Tortenelmi varosreszek terkepi lehatarolasa.jpg" \
  "Tortenelmi varosreszek terkepi lehatarolasa.pdf"
  # 9921x14032

gs \
  -sDEVICE=jpeg \
  -r300 \
  -sPageList=141 \
  -o integr_varosf_strat-141.jpg \
  integr_varosf_strat.pdf
  # 4958x3504

gs \
  -sDEVICE=jpeg \
  -r250 \
  -sPageList=145 \
  -o integr_varosf_strat-145.jpg \
  integr_varosf_strat.pdf
  # 8997x10788
```

## Status

TODO: Mivel elég nagy területet fednek le és jelentős a domborzat,
nem lehet tökéletesen egymásra illeszteni, így használat előtt még egy
picit finomhangolni kell arra a környékre ahol szerkeszteni szeretnénk.
