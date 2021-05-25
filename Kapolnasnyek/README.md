# Kápolnásnyék

```
wget \
  -O "646_rendelet-1-2-melleklet.pdf" \
  "http://kapolnasnyek.hu/download.php?document_id=646"

gs \
  -sDEVICE=jpeg \
  -r150 \
  -o "646_rendelet-1-2-melleklet.jpeg" \
  "646_rendelet-1-2-melleklet.pdf"

cp -a \
  "646_rendelet-1-2-melleklet.jpeg" \
  "646_rendelet-1-2-melleklet-Pettend.jpeg"
```
