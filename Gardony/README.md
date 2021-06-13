# Gárdony

```
wget \
  -nc \
  https://www.gardony.hu/_user/browser/File/2018m%C3%A1rcius/keilbachmarc22/Tervlap%202_3-4-M2.pdf \
  https://www.gardony.hu/_user/browser/File/2018m%C3%A1rcius/keilbachmarc22/Tervlap%207_3_-1-M.pdf \
  https://www.gardony.hu/_user/browser/File/2019augusztus/partners%C3%A9gi%20egyeztet%C3%A9s%20anyagai/4_2_4_M.pdf \
  https://www.gardony.hu/_user/browser/File/2021%20janu%C3%A1r/h%C3%A9sz/4_3_4_M.pdf \
  https://www.gardony.hu/_user/browser/File/2020OKT%C3%93BER/h%C3%A9sz/4_4_1_M2.pdf \
  https://www.gardony.hu/_user/browser/File/2019augusztus/partners%C3%A9gi%20egyeztet%C3%A9s%20anyagai/4_4_2_M3.pdf \
  https://www.gardony.hu/_user/browser/File/2021%20janu%C3%A1r/h%C3%A9sz/4_4_3_M.pdf \
  https://www.gardony.hu/_user/browser/File/2020OKT%C3%93BER/h%C3%A9sz/5_1_1_M3.pdf \
  https://www.gardony.hu/_user/rendeletek/5-1-2M.pdf \
  https://www.gardony.hu/_user/browser/File/2020OKT%C3%93BER/h%C3%A9sz/5_1_3_M4.pdf \
  https://www.gardony.hu/_user/browser/File/2020OKT%C3%93BER/h%C3%A9sz/7_1_3_M2.pdf \
  https://www.gardony.hu/_user/browser/File/2018m%C3%A1rcius/keilbachmarc22/Tervlap%207_2-1-M3.pdf \
  https://www.gardony.hu/_user/rendeletek/7-2-3-M2.pdf \
  https://www.gardony.hu/_user/browser/File/2020OKT%C3%93BER/h%C3%A9sz/7_3_2_M.pdf \
  https://www.gardony.hu/_user/browser/File/2015m%C3%A1jus/Szab_7_3_3.pdf \
  https://www.gardony.hu/_user/rendeletek/7_4_2_M2.pdf \
  https://www.gardony.hu/_user/browser/File/2016okt%C3%B3ber/TARSRESZVETEL1/G%C3%A1rdony-k%C3%B6rnyezet%C3%A9rt%C3%A9kel%C3%A9s.pdf

for F in Terv*.pdf [0-9]*.pdf Szab*.pdf;do
 O="`basename "$F" .pdf`.jpg"
 [ -f "$O" ] ||
  gs -sDEVICE=jpeg -r300 -o "$O" "$F"
done # 4961x3508

gs -sPageList=8 -sDEVICE=jpeg -r600 \
  -o Gárdony-környezetértékelés.jpg \
  Gárdony-környezetértékelés.pdf
  # 4958x7017
```

## TODO

```
11-1a_4_M.pdf
4_4_4_M3.pdf
5_3_1_M3.pdf
5_3_2_M.pdf
5_3_4_M.pdf
6_3_4_M.pdf
8_1_4_M.pdf
8_3_2_M.pdf
melléklet -véleményezési dokumentáció.pdf
Szab 6_4_2.pdf
Végl_kossuth_utca.pdf
```
