# Fehérgyarmat

Fehérgyarmat honlapján elérhetők a [hatályos rendeletek](https://www.fehergyarmat.hu/hatalyos-rendeletek.php). Innen letölthető Fehérgyarmat város önkormányzata képviselő-testületének 15/2019.(IX.02.) önkormányzati rendelete a helyi építési szabályzatról, amely tartalmazza az utakat, a telekhatárokat és az épületeket. Külön szelvények érhetők el a belterülethez és a külterülethez. Ha be szeretnéd tölteni a JOSM-be, akkor futtasd le a következő parancsokat.

Töltsd le a helyi építési szabályzatot. Körülbelül 6 MB kerül letöltésre.

```
wget https://www.fehergyarmat.hu/files/2019-0829-15-rend-kiv.docx
```

Szedd ki a dokumentumból a képeket. A képek mérete körülbelül 5,8 MB.

```
unzip -p 2019-0829-15-rend-kiv.docx word/media/image1.png > belterulet-A.png
unzip -p 2019-0829-15-rend-kiv.docx word/media/image2.png > belterulet-B.png
unzip -p 2019-0829-15-rend-kiv.docx word/media/image3.png > jelmagyarazat.png
unzip -p 2019-0829-15-rend-kiv.docx word/media/image4.png > kulterulet-A.png
unzip -p 2019-0829-15-rend-kiv.docx word/media/image5.png > kulterulet-B.png
```

Nyisd meg a képfájlokat a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.
