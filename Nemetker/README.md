# Németkér

Németkér [helyi építési szabályzatának](http://nemetker.hu/helyi_epitesi_szabalyzat) melléklete tartalmazza az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a szabályozási terveket.

```
wget http://nemetker.hu/uploads/Szab%C3%A1lyoz%C3%A1si%20terv%201..pdf -O Nemetker-1.pdf
wget http://nemetker.hu/uploads/Szab%C3%A1lyoz%C3%A1si%20terv%202..pdf -O Nemetker-2.pdf
```

Alakítsd át a PDF-fájlokat JPG-fájlokká.

```
gs -sDEVICE=jpeg -r150 -o Nemetker-1.jpg Nemetker-1.pdf
gs -sDEVICE=jpeg -r150 -o Nemetker-2.jpg Nemetker-2.pdf
```
