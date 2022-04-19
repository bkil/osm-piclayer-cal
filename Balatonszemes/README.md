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


## Berzsenyi utcai szabadstrand

Balatonszemes honlapján a Berzsenyi utcai szabadstrand fejlesztéséről szóló [hír](https://www.balatonszemes.hu/1355-2/) mellékletében található egy 1:500 méretű [helyszínrajz](https://www.balatonszemes.hu/wp-content/uploads/2020/10/Balatonszemes-strand-E%CC%81PU%CC%88LET_E%CC%81-0-Helyszi%CC%81nrajz-M1_500.pdf).

Töltsd le a hírben lévő helyszínrajzot. A fájl mérete körülbelül 830 kB.

```
wget "https://www.balatonszemes.hu/wp-content/uploads/2020/10/Balatonszemes-strand-E%CC%81PU%CC%88LET_E%CC%81-0-Helyszi%CC%81nrajz-M1_500.pdf" -O berzsenyi-strand.pdf
```

Alakítsd át a PDF-fájlt JPG-fájllá. Az eredményül kapott kép mérete körülbelül 1,8 MB.

```
gs -sDEVICE=jpeg -r150 -o berzsenyi-strand.jpg berzsenyi-strand.pdf
```
