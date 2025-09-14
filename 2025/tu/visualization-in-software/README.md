# Visualization in Software

Date: 2025-09-24
Presented At: Towson University
Presented For: Software Engineering Club - Undergraduate and Graduate Students

## Using Quarto

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt --require-virtualenv
quarto render slides.qmd
```

## Generating QR Codes

```
qrencode -o qr_jllovet_com.png "https://jllovet.com"
qrencode -o qr_slides.png "https://jllovet.github.io/talks/2025/tu/visualization-in-software/slides"
```

See: [https://github.com/fukuchi/libqrencode](https://github.com/fukuchi/libqrencode)