# AdventureWorks – Försäljningsanalys

Detta projekt innehåller en försäljningsanalys av AdventureWorks-databasen.
Syftet med analysen är att undersöka försäljningsmönster utifrån produkter, tid, regioner och kundtyper.

Analysen är genomförd i en Jupyter Notebook där data hämtas från en SQL Server-databas med hjälp av SQL,
och analyseras samt visualiseras vidare i Python med Pandas och Matplotlib.

---

## Projektstruktur

- `notebooks/`
  - `adventureworks_sales_analysis.ipynb`  
    Innehåller hela analysen inklusive SQL-frågor, visualiseringar, djupanalys och sammanfattning.

- `.gitignore`  
  Används för att exkludera lokala filer som virtuell miljö och databasbackup.

- `.venv/`  
  Lokal virtuell Python-miljö (ingår ej i GitHub-repot).

---

## Databas

Databasen som används är AdventureWorks2025 och körs lokalt i SQL Server via Docker Desktop på Windows.
Databasen har återställts från en backupfil (`AdventureWorks2025.bak`) som tillhandahållits i kursen.
Backupfilen ingår inte i GitHub-repot.

---

## Genomförande

Arbetet har genomförts i följande steg:

1. Uppstart av SQL Server i Docker Desktop
2. Återställning av AdventureWorks-databasen
3. Anslutning till databasen från Python i Jupyter Notebook
4. Insamling av data med SQL-frågor
5. Analys och visualisering av data i Pandas och Matplotlib
6. Fördjupad analys samt sammanfattning av resultat

Alla analyser och visualiseringar är dokumenterade direkt i notebooken.
