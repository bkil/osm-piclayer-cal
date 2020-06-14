# Településrendezési tervek JOSM-hez

A településrendezési terveket és a helyi vagy kerületi építési szabályzatokat nagyon sok önkormányzat elérhetővé teszi a honlapján. Ezeket a terveket és szabályzatokat a megfelelő átalakítással lehetőség van betölteni a JOSM szerkesztőbe, hogy segítse a rajzolást. Ez a tároló ehhez tartalmaz georeferálási adatokat.

A tervek és szabályzatok betöltéséhez a JOSM szerkesztőben telepíteni kell a [PicLayer](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/PicLayer) bővítményt, illetve szükséged lesz néhány parancssoros programra is a letöltéshez.


## A PicLayer bővítmény telepítése

A *PicLayer* bővítmény telepítéséhez:

1. Kattints a *Szerkesztés* → *Beállítások…* menüpontra a JOSM-ben.
2. Kattints a *Bővítmények* lapra (felülről a 4. fül).
3. Kezd el gépelni a *PicLayer* szót. Automatikusan meg fogja találni.
4. Jelöld be a jelölőnégyzetet, és kattints az *OK* gombra.


## A parancssoros eszközök telepítése

A használathoz szükséged lesz a következő parancssoros programokra:

- `ghostscript`: a letöltött PDF-fájlok képpé alakításához.
- `git`: ezen tároló klónozásához és frissítéséhez.
- `unzip`: a DOCX formátumú fájlok kibontásához.
- `wget`: a településrendezési tervek és a helyi vagy kerületi építési szabályzatok letöltéséhez.

Debian, Ubuntu, Linux Mint és az ezekre épülő változatoknál:

```
sudo apt install ghostscript git unzip wget
```

Red Hat, CentOS, Fedora és az ezekre épülő változatoknál:

```
dnf install ghostscript git unzip wget
```

Windows használatakor töltsd le és telepítsd a következő programokat:

- [Ghostscript for Windows](https://www.ghostscript.com/download/gsdnld.html)
- [Git for Windows](https://git-scm.com/download/win)
- [Wget for Windows](http://gnuwin32.sourceforge.net/packages/wget.htm)


## Használat

1. Klónozd a git tárolót. A tároló tartalmazza a kalibrációs adatokat, de a forrásfájlokat nem.

   ```
   git clone osm-piclayer-cal
   ```

2. Nyisd meg a kívánt település mappáját, és kövest a `README.md` fájlban leírt utasításokat a forrásfájlok letöltéséhez és feldolgozásához.
3. Nyisd meg a letöltött és feldolgozott képfájlt a JOSM szerkesztővel a *Légi felvétel* → *Új kép réteg fájlból…* menüpont használatával.


## Jogi nyilatkozat

A git tároló csak a kalibrációs adatokat tartalmazza a georeferáláshoz, ami ODbL licenc alatt van közzétéve. A településrendezési terveket és a helyi vagy kerületi építési szabályzatokat neked kell letölteni az említett weboldalakról.

Az átrajzolás nem pixelre pontosan történik, így a használatkor nem sértünk adatbázisjogot. A jogszabályok és rendeletek szövege – beleértve a településrendezési terveket és a helyi vagy kerületi építési szabályzatokat is – bárki számára elérhető és használható.
