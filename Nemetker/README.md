# Németkér

Németkér [helyi építési szabályzatának](http://nemetker.hu/helyi_epitesi_szabalyzat) szabályozási terve tartalmazza az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a szabályozási terveket. Körülbelül 5,6 MB kerül letöltésre.

```
wget http://nemetker.hu/uploads/Szab%C3%A1lyoz%C3%A1si%20terv%201..pdf -O Nemetker-1.pdf
wget http://nemetker.hu/uploads/Szab%C3%A1lyoz%C3%A1si%20terv%202..pdf -O Nemetker-2.pdf
```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 11,5 MB.

```
gs -sDEVICE=jpeg -r150 -o Nemetker-1.jpg Nemetker-1.pdf
gs -sDEVICE=jpeg -r150 -o Nemetker-2.jpg Nemetker-2.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
