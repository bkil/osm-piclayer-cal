# Budapest XXII. kerület

Budafok-Tétény [kerületi építési szabályzatának](https://budafokteteny.hu/ugyintezes/foepiteszi-es-varosrendezesi-iroda#%C3%BAj%20k%C3%A9sz) szabályozási terve tartalmazza az utakat, a telekhatárokat és az épületeket is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a szabályozási terveket. Körülbelül 242 MB kerül letöltésre.

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

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 57 MB.

```
gs -sDEVICE=jpeg -r150 -o SZ01.jpg SZ01.pdf
gs -sDEVICE=jpeg -r150 -o SZ02.jpg SZ02.pdf
gs -sDEVICE=jpeg -r150 -o SZ04.jpg SZ04.pdf
gs -sDEVICE=jpeg -r150 -o SZ05.jpg SZ05.pdf
gs -sDEVICE=jpeg -r150 -o SZ06.jpg SZ06.pdf
gs -sDEVICE=jpeg -r150 -o SZ08.jpg SZ08.pdf
gs -sDEVICE=jpeg -r150 -o SZ10.jpg SZ10.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.


# Térképet tartalmazó hírek

A következő weboldalak és hírek térképmásolatot, térképrajzot, látványterveket, alaprajzokat és helyszínrajzokat is tartalmaznak. A letöltésük után a fent ismertetett módon lehet megnyitni azokat a JOSM szerkesztővel.


## Dukát utca és környéke

A Dukát utcai útépítés miatt oszlopáthelyezés szükséges, ami következtében az Elmű szünetelteti szolgáltatását a Dukát utca környékén néhány utcában. Forrás: [Budafok-Tétény Önkormányzatának hivatalos hírlevele](https://budafokteteny.hu/hir/aramszunet-a-dukat-utcaban-es-kornyeken).

A térképmelléklet közvetlenül a hírből vagy a következő parancs használatával tölthető le. A fájl mérete körülbelül 470 KB.

```
wget https://budafokteteny.hu/uploads/files/2017/sajto/elmu.PNG -O dukat-utca.png
```


## József Attila utcai lakótelep

A József Attila (kísérleti) lakótelep köztereinek megújítási javaslata szerepel [ebben az önkormányzati hírben](https://www.budafokteteny.hu/hir/megujulhatnak-a-jozsef-attila-kiserleti-lakotelep-kozterei). A cikk mellékleteként megtalálható egy részletes helyszínrajz is. Fontos azonban figyelembe venni, hogy ez csak egy terv. A megvalósult fejlesztés eltérő lehet, ezért érdemes összevetni az ortofotókkal.

A helyszínrajz közvetlenül a hírből vagy a következő parancs használatával tölthető le. A fájl mérete körülbelül 480 KB.

```
wget https://www.budafokteteny.hu/uploads/images/galeria/jaltp2/JA_LTP_szinesterv.jpg -O jozsef-attila-lakotelep.jpg
```


## Piactér

Budafok-Tétény Önkormányzatának hivatalos hírlevelében megjelent [Nyárra készül a Piactér](https://budafokteteny.hu/hir/nyarra-keszul-a-piacter) cikkben részletes helyszínrajz található a Piactérről.

A helyszínrajz közvetlenül a hírből vagy a következő parancs használatával tölthető le. A fájl mérete körülbelül 408 KB.

```
wget https://budafokteteny.hu/uploads/images/galeria/napvitorlak/K%C3%A9pkiv%C3%A1g%C3%A1s2.PNG -O piacter.png
```


## Szent Flórián tér

A Szent Flórián teret és a Szentháromság teret 2013-ban felújították. A [Zöldkalauz](https://zoldkalauz.hu/szentharomsag-ter-szent-florian-ter) honlapján részletes alaprajz található a térről.

Az alaprajz közvetlenül a honlapról vagy a következő parancs használatával tölthető le. A fájl mérete körülbelül 103 KB.

```
wget https://zoldkalauz.hu/files/images/420/nt-terv.jpg -O szent-florian-ter.jpg
```


## Szent István tér

Az S-Tér Kft. [referenciái](http://www.s-ter.hu/hu/referenciak/kozter-kozpark/szent-istvan-ter-es-mozi-elotti-ter) között megtalálhatók a Szent István tér felújításához kapcsolódó tervek is.

A látványterv közvetlenül a honlapról vagy a következő parancs használatával tölthető le. A fájl mérete körülbelül 32 MB.

```
wget http://www.s-ter.hu/sites/default/files/plans/szent-istvan-ter-es-mozi-elotti-ter-megujitasa/t2017pszentistvanparkmodszinaesalaprajz190916.png -O szent-istvan-ter.png
```
