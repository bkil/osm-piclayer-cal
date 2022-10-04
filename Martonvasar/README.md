# Martonvásár

A település [honlapján lévő hírekben](https://www.martonvasar.hu/epitesi_ugyek) található két bejegyzés a helyi építési szabályok módosításáról. A szelvényeken látszanak a helyrajzi számok és a házszámok is. Az újabb bejegyzésből a 4-es szelvény, a régebbiből a 2-es szelvény hiányzik, ezért mindkettő mellékletét le kell tölteni, hogy meglegyen az összes szelvény.

Töltsd le a szabályozási terveket. Körülbelül 77 MB kerül letöltésre.

```
wget https://www.martonvasar.hu/document/1546 -O 1546.zip
wget https://www.martonvasar.hu/document/1980 -O 1980.zip
```

Bontsd ki a tömörített fájlokból a szükséges tervlapokat. Körülbelül 19,8 MB lesz a kibontott PDF-fájlok mérete.

```
unzip 1546.zip Martonvasar_munkakozi_anyag_2020616/Tervlapok/SZT1_4.pdf Martonvasar_munkakozi_anyag_2020616/Tervlapok/SZT1_6-7.pdf
unzip 1980.zip Tervlapok/Martonvasar_mod_7_jelmagyarazat.pdf Tervlapok/Martonvasar_mod_7_SZT1_1.pdf Tervlapok/Martonvasar_mod_7_SZT1_2.pdf Tervlapok/Martonvasar_mod_7_SZT1_3.pdf Tervlapok/Martonvasar_mod_7_SZT1_5_A.pdf
```

Alakítsd át a PDF-fájlokat JPG-fájlokká. A 6-os és a 7-es szelvény egy oldalon van. A daraboláshoz a parancssoros [ImageMagick](https://imagemagick.org/) programot használtam. Az eredményül kapott képek mérete körülbelül 15,6 MB.

```
gs -sDEVICE=jpeg -r150 -o SZ01-20210813.jpg Tervlapok/Martonvasar_mod_7_SZT1_1.pdf
gs -sDEVICE=jpeg -r150 -o SZ02-20210813.jpg Tervlapok/Martonvasar_mod_7_SZT1_2.pdf
gs -sDEVICE=jpeg -r150 -o SZ03-20210813.jpg Tervlapok/Martonvasar_mod_7_SZT1_3.pdf
gs -sDEVICE=jpeg -r150 -o SZ04-20200610.jpg Martonvasar_munkakozi_anyag_2020616/Tervlapok/SZT1_4.pdf
gs -sDEVICE=jpeg -r150 -o SZ05-20210813.jpg Tervlapok/Martonvasar_mod_7_SZT1_5_A.pdf
gs -sDEVICE=jpeg -r150 -o SZ06-07.jpg Martonvasar_munkakozi_anyag_2020616/Tervlapok/SZT1_6-7.pdf
convert SZ06-07.jpg -crop 2420x3400+180+270 SZ06-20200610.jpg
convert SZ06-07.jpg -crop 2460x3400+2700+270 SZ07-20200610.jpg
```

Egy kis takarítás, mert vannak olyan fájlok, amelyek csak egy további lépéshez kellettek. Ezek törölhetők. Windowson `mv` helyett `move` és `rm` helyett `del` parancs használható.

```
mv Tervlapok/Martonvasar_mod_7_jelmagyarazat.pdf Jelmagyarazat.pdf
rm -r Martonvasar_munkakozi_anyag_2020616
rm -r Tervlapok
rm SZ06-07.jpg
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
