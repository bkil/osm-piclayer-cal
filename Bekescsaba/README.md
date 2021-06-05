# Békéscsaba

## Területi védelem 2020-01-26

* Telekhatárok, természetvédelmi területek, lakótelepek

```
wget \
  -nc \
  -O 6-melleklet.pdf \
  https://bekescsaba.hu/download/115/6-melleklet &&

gs \
  -sDEVICE=jpeg \
  -r450 \
  -o "6-melleklet.jpg" \
  "6-melleklet.pdf"
  # 7438x5256
```

## Választási körzetek 2019-10

* Utcanevek, házszámok, épületek, külterületen helyrajzi számok

```
wget \
  -nc \
  -O valasztasi-terkep-2019-oktober.pdf \
  https://bekescsaba.hu/download/1295/valasztasi-terkep-2019-oktober &&

gs \
  -sDEVICE=jpeg \
  -r300 \
  -o "valasztasi-terkep-2019-oktober.jpg" \
  "valasztasi-terkep-2019-oktober.pdf"
  # 29528x23622
```

Nagyításai sok kicsi fájlban is elérhető, vélhetően azonos információtartalommal:

* `2-sz-egyeni-valasztokeruelet.pdf`
* stb: https://bekescsaba.hu/valasztasi-terkepek

### Szavazóköri leírás 2019

* utcanevek, néhány házszámtartomány

* `szavazokoeri-leiras-valasztokerueletenkent.pdf`
* `szavazokoeri-leiras-utcankenti.pdf`

## Turista térkép

* 2018-06-25
* Utcanevek, épületek, házszámok, külterületi helyrajzi számok
* https://bekescsaba.hu/terkepek

```
wget \
  -nc \
  -O turista-terkep.pdf \
  https://bekescsaba.hu/download/121/turista-terkep &&

gs \
  -sDEVICE=jpeg \
  -r150 \
  -o "turista-terkep.jpg" \
  "turista-terkep.pdf"
  # 14764x11811
```

## Szabályozási terv szelvényei

Tartalmaz telekhatárokat, utcaneveket, épületeket, házszámokat, helyrajzi számokat, egyes gyalogutakat, építési megszorításokat, védett fasorok, stb. Sok kicsi fájlban elérhető:

* _"Szabályozási terv M=1:4000"_
  * https://bekescsaba.hu/terkepek
* Áttekintés: `szelvenyezes.pdf`
  * https://bekescsaba.hu/download/1162/szelvenyezes
* Egy példa szelvény: `24c.pdf`

## Kamerák

Térképvázlattal illusztrált és szövegesen leírva az elhelyezkedést és a megfigyelt helyszínt:

* https://bekescsaba.hu/terfigyelo-kamerak
* `1-szent-istvan-ter-es-koernyeke-2013.pdf`
* `2-csabapark-2014.pdf`
* `3-andrassy-ut-es-koernyeke-2015.pdf`
* `4-vasutallomas-es-koernyeke-2016.pdf`
* `5-uetem-munkacsy-negyed-2018.pdf`
* `6-uetem-oenkormanyzati-forrasbol-terfigyelo-2019.pdf`
* `7-uetem-munkacsy-negyed-2020.pdf`
* `8-uetem-smart-projekt-10-kamera-2021.pdf` - itt a térkép már OpenStreetMap alapú!
