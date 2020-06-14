# Budapest XXII. kerület

Budafok-Tétény [helyi építési szabályzatának](https://budafokteteny.hu/ugyintezes/foepiteszi-es-varosrendezesi-iroda#%C3%BAj%20k%C3%A9sz) melléklete tartalmazza az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a szabályozási terveket.

```
wget https://budafokteteny.hu/uploads/files/1525423287.jpg -O Szelvenyezes.jpg
wget https://budafokteteny.hu/uploads/files/1558607621.pdf -O SZ01.pdf
wget https://budafokteteny.hu/uploads/files/1558607632.pdf -O SZ02.pdf
wget https://budafokteteny.hu/uploads/files/1525422893.jpg -O SZ03.jpg
wget https://budafokteteny.hu/uploads/files/1558607643.pdf -O SZ04.pdf
wget https://budafokteteny.hu/uploads/files/1558607674.pdf -O SZ05.pdf
wget https://budafokteteny.hu/uploads/files/1558607682.pdf -O SZ06.pdf
wget https://budafokteteny.hu/uploads/files/1575464667.jpg -O SZ07.jpg
wget https://budafokteteny.hu/uploads/files/1558607710.pdf -O SZ08.pdf
wget https://budafokteteny.hu/uploads/files/1525423154.jpg -O SZ09.jpg
wget https://budafokteteny.hu/uploads/files/1558607721.pdf -O SZ10.pdf
wget https://budafokteteny.hu/uploads/files/1525423221.jpg -O SZ11.jpg
wget https://budafokteteny.hu/uploads/files/1525423259.jpg -O SZ12.jpg
```

Alakítsd át a PDF-fájlokat JPG-fájlokká.

```
gs -sDEVICE=jpeg -r150 -o SZ01.jpg SZ01.pdf
gs -sDEVICE=jpeg -r150 -o SZ02.jpg SZ02.pdf
gs -sDEVICE=jpeg -r150 -o SZ04.jpg SZ04.pdf
gs -sDEVICE=jpeg -r150 -o SZ05.jpg SZ05.pdf
gs -sDEVICE=jpeg -r150 -o SZ06.jpg SZ06.pdf
gs -sDEVICE=jpeg -r150 -o SZ08.jpg SZ08.pdf
gs -sDEVICE=jpeg -r150 -o SZ10.jpg SZ10.pdf
```


# Térképet tartalmazó hírek

A következő hírek térképmásolatot vagy térképrajzot is tartalmaznak.


## Áramszünet a Dukát utcában és környékén

A Dukát utcai útépítés miatt oszlopáthelyezés szükséges, ami következtében az Elmű szünetelteti szolgáltatását a Dukát utca környékén néhány utcában. Forrás: [Budafok-Tétény Önkormányzatának hivatalos hírlevele](https://budafokteteny.hu/hir/aramszunet-a-dukat-utcaban-es-kornyeken).

A térképmelléklet közvetlenül a hírből vagy a következő parancs használatával tölthető le.

```
wget https://budafokteteny.hu/uploads/files/2017/sajto/elmu.PNG -O dukat-utca.png
```
