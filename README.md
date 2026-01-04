# AdventureWorks – Försäljningsanalys

Detta projekt innehåller en försäljningsanalys av AdventureWorks-databasen.

Analysen är genomförd i en Jupyter Notebook där data hämtas från en SQL Server-databas och analyseras samt visualiseras med Pandas och Matplotlib.

---

## Projektstruktur

- `notebooks/`
  - `adventureworks_sales_analysis.ipynb`  
    Innehåller hela analysen, SQL-frågor, visualiseringar och reflektioner.

- `data/`  
  Innehåller backupfilen `AdventureWorks2025.bak` (ingår ej i GitHub-repot).

- `.venv/`  
  Lokal virtuell Python-miljö (ingår ej i GitHub).

---

## Databas

Databasen körs lokalt i SQL Server via Docker Desktop på Windows.  
Backupfilen `AdventureWorks2025.bak` återställs i containern och används sedan av notebooken via en Python-anslutning.

---

## Hur projektet körs

1. SQL Server startas i Docker Desktop
2. Databasen återställs från backupfil
3. Virtuell Python-miljö aktiveras
4. Notebooken körs cell för cell

Alla analyser och visualiseringar finns dokumenterade direkt i notebooken.
