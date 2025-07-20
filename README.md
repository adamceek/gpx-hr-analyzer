# Heart Rate Comparison: Garmin vs Huawei

📊 Skript pre porovnanie presnosti merania srdcového tepu medzi dvoma zariadeniami (napr. Garmin HRM a Huawei Watch Fit 2) pomocou `.gpx` súborov.

## 🚀 Funkcie

- Nahranie a porovnanie dvoch `.gpx` súborov obsahujúcich HR dáta
- Automatická detekcia optimálneho časového posunu
- Vizualizácia výsledkov
- Export do `.tsv` a ukladanie grafov
- Podpora detekcie výpadkov HR záznamov

## 📂 Štruktúra súborov

- `porovnanie.ipynb` – Hlavný Colab notebook
- `porovnanie.py` – Alternatíva pre lokálne spustenie (voliteľné)

## 📦 Závislosti

Spúšťané v Google Colab (štandardné knižnice):
- `matplotlib`
- `numpy`
- `xml`
- `datetime`

## 📁 Použitie

1. Otvor `porovnanie.ipynb` v Google Colab
2. Nahraj 2 GPX súbory
3. Skript automaticky:
    - Deteguje dátum a typ aktivity
    - Porovná HR záznamy
    - Uloží graf a výsledky

## 🧠 Poznámka

Tento projekt vznikol ako osobný nástroj na analýzu tréningových dát. Môžeš si ho upraviť podľa svojich potrieb.

