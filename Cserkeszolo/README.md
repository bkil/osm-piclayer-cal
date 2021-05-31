# Cserkeszőlő

```
wget \
  "https://www.cserkeszolo.hu/storage/documents/epitesugyi/szabtervbel.pdf" \
  "https://www.cserkeszolo.hu/storage/documents/epitesugyi/szabtervkul.pdf"

gs \
  -sDEVICE=jpeg \
  -r300 \
  -o "szabtervkul.jpeg" \
  "szabtervkul.pdf"

gs \
  -sDEVICE=jpeg \
  -r300 \
  -o "szabtervbel.jpeg" \
  "szabtervbel.pdf"
```
