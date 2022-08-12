# Százhalombatta

## TSZT 2015-2017

```
wget \
  -nc \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt1_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt2_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt3_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/rendelet/2017/3-2017m_1.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt5_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/rendelet/2017/3-2017m_2.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt7_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt8_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt9_2015_12.pdf \
  https://battanet.hu/battanet4/userfiles/file/2017/1107/szazhalombatta_szt10_2015_12.pdf &&

for F in *.pdf; do
  O="`basename "$F" .pdf`.jpeg"
  [ -f "$O" ] ||
  gs \
    -sDEVICE=jpeg \
    -r300 \
    -o "$O" \
    "$F"
    # 10808x16183
done
```

Sources:

* https://battanet.hu/dokumentumok-listanezet/?ds=2&cat1=5
