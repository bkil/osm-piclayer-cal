# Papkeszi

Papkeszi [belterületi szabályozási terve](https://papkeszi.hu/onkormanyzat/telepulesrendezes/) tartalmazza az utakat, a telekhatárokat, az épületeket és a házszámokat is. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

1. Töltsd le a szabályozási terveket. Körülbelül 17 MB kerül letöltésre.

```
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_1.pdf -O Papkeszi-1.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_2.pdf -O Papkeszi-2.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_3.pdf -O Papkeszi-3.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_4.pdf -O Papkeszi-4.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_5.pdf -O Papkeszi-5.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_6.pdf -O Papkeszi-6.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_7.pdf -O Papkeszi-7.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter_szt2.pdf -O Papkeszi-szt2.pdf
wget https://papkeszi.hu/wp-content/themes/Glorius/doksik/Letoltes/telepulesrendezes/belter.jpg -O Szelvenyezes.jpg
```

2. Alakítsd át a PDF-fájlokat JPG-fájlokká. Az eredményül kapott képek mérete körülbelül 5,1 MB.

```
gs -sDEVICE=jpeg -r150 -o Papkeszi-1.jpg Papkeszi-1.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-2.jpg Papkeszi-2.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-3.jpg Papkeszi-3.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-4.jpg Papkeszi-4.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-5.jpg Papkeszi-5.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-6.jpg Papkeszi-6.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-7.jpg Papkeszi-7.pdf
gs -sDEVICE=jpeg -r150 -o Papkeszi-szt2.jpg Papkeszi-szt2.pdf
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
