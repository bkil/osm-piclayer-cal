# Várgesztes

Várgesztes [helyi építési szabályzatának](http://www.vargesztes.hu/onkormanyzat/szabalyzatok-tervek) belterületi szabályozási tervei tartalmazzák az utakat, a telekhatárokat, az épületeket és a házszámokat is. Különálló szelvényen található a Villapark, illetve elérhető a szabályozási terv a közigazgatási területre is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a belterületi és a közigazgatási területre vonatkozó szabályozási terveket. Körülbelül 3,4 MB kerül letöltésre.

```
wget http://www.vargesztes.hu/Content/GetFile/162 -O Vargesztes.pdf
wget http://www.vargesztes.hu/Content/GetFile/164 -O Vargesztes-Villapark.pdf
wget http://www.vargesztes.hu/Content/GetFile/165 -O Vargesztes-kulterulet.pdf
```

Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 6,8 MB.

```
gs -sDEVICE=jpeg -r150 -o Vargesztes.jpg Vargesztes.pdf
gs -sDEVICE=jpeg -r150 -o Vargesztes-Villapark.jpg Vargesztes-Villapark.pdf
gs -sDEVICE=jpeg -r150 -o Vargesztes-kulterulet.jpg Vargesztes-kulterulet.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
