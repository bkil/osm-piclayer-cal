# Szántód

Szántód [szabályozási tervei](https://szantod.hu/dokumentum-kategoria/rendezesi-terv/) között szerepelnek a belterületi és külterületi szabályozási tervek, amelyek tartalmazzák az utakat, a telekhatárokat, az épületeket, a házszámokat és a helyrajzi számokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi szabályozási terveket. Körülbelül 4,4 MB kerül letöltésre.

```
wget https://szantod.hu/wp-content/uploads/2020/10/10.2-SZT-2.1-Belterulet-szabalyozasi-terv-M1_2000.pdf -O SZT-21.pdf
wget https://szantod.hu/wp-content/uploads/2020/10/10.2-SZT-2.2-Belterulet-szabalyozasi-terv-M1_2000.pdf -O SZT-22.pdf
wget https://szantod.hu/wp-content/uploads/2020/10/10.1-SZT-1-Kulterulet-szabalyozasi-terv-M1_8000.pdf -O SZT-kulterulet.pdf

```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 11,7 MB.

```
gs -sDEVICE=jpeg -r150 -o SZT-21.jpg SZT-21.pdf
gs -sDEVICE=jpeg -r150 -o SZT-22.jpg SZT-22.pdf
gs -sDEVICE=jpeg -r150 -o SZT-kulterulet.jpg SZT-kulterulet.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
