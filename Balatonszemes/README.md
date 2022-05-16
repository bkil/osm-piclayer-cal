# Balatonszemes

Balatonszemes község Képviselő-testületének [12/2010.(V.17.) önkormányzati rendelete](https://or.njt.hu/onkormanyzati-rendelet/549326) Balatonszemes község helyi építési szabályzatáról szól. A rendelet mellékletei tartalmazzák az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi és külterületi szabályozási terveket. Körülbelül 8,9 MB kerül letöltésre.

```
wget "https://or.njt.hu/download/2460/resources/EJR_14664569-1._mell_klet_15-2021__XI.10.__r-el_m_dos_tva.pdf" -O SZ01-202111.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14664583-2.mell_klet_10-2016__V.26.__r-el_m_dos_tva.pdf" -O SZ02-201606.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14664587-3._mell_klet_15-2021__XI.10.__r-el_m_dos_tva.pdf" -O SZ03-202111.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14664589-4._mell_klet_18-2019__XII.17.__r-el_m_dos_tva.pdf" -O SZ04-201912.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14664592-5.mell_klete_17-2016__XII.12.__r-el_m_dos_tva.pdf" -O SZ05-201612.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14664593-6.mell_klete_17-2016__XII.12.__r-el_m_dos_tva.pdf" -O SZ06-201612.pdf
wget "https://or.njt.hu/download/2460/resources/EJR_14665234-9.melleklet_17-2016__XII.12.__r-el_m_dos_tva.pdf" -O KM09-201612.pdf
```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 17,4 MB.

```
gs -sDEVICE=jpeg -r150 -o SZ01-202111.jpg SZ01-202111.pdf
gs -sDEVICE=jpeg -r150 -o SZ02-201606.jpg SZ02-201606.pdf
gs -sDEVICE=jpeg -r150 -o SZ03-202111.jpg SZ03-202111.pdf
gs -sDEVICE=jpeg -r150 -o SZ04-201912.jpg SZ04-201912.pdf
gs -sDEVICE=jpeg -r150 -o SZ05-201612.jpg SZ05-201612.pdf
gs -sDEVICE=jpeg -r150 -o SZ06-201612.jpg SZ06-201612.pdf
gs -sDEVICE=jpeg -r150 -o KM09-201612.jpg KM09-201612.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.

---

**MEGSZŰNT**, már nem érhető el:

Balatonszemes [helyi építési szabályzatának](http://www.balatonszemes.hu/dokumentumok/dokumentumnyitva.php?id=29) belterületi szabályozási tervei tartalmazzák az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi szabályozási terveket. Körülbelül 23,8 MB kerül letöltésre.

```
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=237" -O SZ01-2009.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=238" -O SZ02-2009.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=243" -O SZ03-2009.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=239" -O SZ04-2009.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=240" -O SZ05-2009.pdf
wget "http://www.balatonszemes.hu/dokumentumok/opendoc.php?type=bin&id=241" -O SZ06-2009.pdf

```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 17,1 MB.

```
gs -sDEVICE=jpeg -r150 -o SZ01-2009.jpg SZ01-2009.pdf
gs -sDEVICE=jpeg -r150 -o SZ02-2009.jpg SZ02-2009.pdf
gs -sDEVICE=jpeg -r150 -o SZ03-2009.jpg SZ03-2009.pdf
gs -sDEVICE=jpeg -r150 -o SZ04-2009.jpg SZ04-2009.pdf
gs -sDEVICE=jpeg -r150 -o SZ05-2009.jpg SZ05-2009.pdf
gs -sDEVICE=jpeg -r150 -o SZ06-2009.jpg SZ06-2009.pdf
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
