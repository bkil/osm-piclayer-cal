# Vilonya

Vilonya [helyi építési szabályzatának](http://vilonya.eu/vinula/helyi-epitesi-szabalyzat-2/) belterületi szabályozása tartalmazza az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi szabályozást. Körülbelül 600 KB kerül letöltésre.

```
wget http://www.vilonya.eu/data/onkormanyzat/HESZ-Vilonya/V_Belter-szabalyozas.pdf -O Vilonya.pdf
```

Alakítsd át a PDF-fájlt JPG-fájllá. Az eredményül kapott kép mérete körülbelül 3,1 MB.

```
gs -sDEVICE=jpeg -r480 -o Vilonya.jpg Vilonya.pdf
```

Nyisd meg a képfájlt a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
