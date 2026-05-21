# KK1 Rymduppskjutningar 1957–2026

Analys av orbital pålitlighet, uppskjutningstakt och världskraft baserat på Jonathan McDowells GCAT-katalog https://planet4589.org/space/gcat/.

## Setup

### 1. Installera Python paketen

```
pip install -r requirements.txt

```

### 2. Ladda ner datasetet

Hämta dessa två filer och skapa mappen `dataset/` och placera dom i den.

- `satcat.tsv` - alla satelliter, direkt länk här https://planet4589.org/space/gcat/tsv/cat/satcat.tsv
- `launch.tsv` - alla uppskjutningar, direkt länk här https://planet4589.org/space/gcat/tsv/launch/launch.tsv

### 3. Kör notebooken

Öppna `notebook.ipynb` och kör kod cellerna i ordning.
