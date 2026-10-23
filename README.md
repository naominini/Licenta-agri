# Analiza Datelor Agricole

Proiectul urmareste prelucrarea si analiza datelor colectate de o statie meteo si senzori de sol, pentru identificarea relatiilor dintre factorii meteorologici si proprietatile solului.

## Ce am realizat
- Incarcarea si explorarea datasetului cu 12 tipuri de masuratori.
- Verificarea valorilor NULL, duplicatelor si outlierilor.
- Analiza frecventei citirilor si a sincronizarii senzorilor.
- Crearea a doua Fact Tables:
  - **fact_agriculture_raw** - 65.096 randuri, pastreaza toate masuratorile originale.
  - **fact_agriculture_analytic** - 48.514 randuri, cu sincronizare temporala de maximum 5 minute.
- Exportul ambelor tabele in format Excel.

## Path
Cele 2 fact table-uri se afla [aici.](Data/output)