# Balatonszemes

Balatonszemes [helyi építési szabályzatának](http://www.balatonszemes.hu/dokumentumok/dokumentumnyitva.php?id=29) belterületi szabályozási tervei tartalmazzák az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi szabályozási terveket. Körülbelül 23,8 MB kerül letöltésre.

```
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=237" -O SZ01.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=238" -O SZ02.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=243" -O SZ03.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=239" -O SZ04.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=240" -O SZ05.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=241" -O SZ06.pdf

```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 17,1 MB.

```
gs -sDEVICE=jpeg -r150 -o SZ01.jpg SZ01.pdf
gs -sDEVICE=jpeg -r150 -o SZ02.jpg SZ02.pdf
gs -sDEVICE=jpeg -r150 -o SZ03.jpg SZ03.pdf
gs -sDEVICE=jpeg -r150 -o SZ04.jpg SZ04.pdf
gs -sDEVICE=jpeg -r150 -o SZ05.jpg SZ05.pdf
gs -sDEVICE=jpeg -r150 -o SZ06.jpg SZ06.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.


## Dr. Kiss Ödön Orvosi Rendelő

Balatonszemes honlapjára fel lett töltve az orvosi rendelő [alaprajza](https://www.balatonszemes.hu/wp-content/uploads/images/alaprajz1.jpg).

Az alaprajz a következő parancs használatával tölthető le. A fájl mérete körülbelül 2,9 MB.

```
wget "https://www.balatonszemes.hu/wp-content/uploads/images/alaprajz1.jpg" -O orvosi-rendelo.jpg
```
