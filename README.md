# Analys av CO₂-utsläpp och Naturkatastrofer (1980–2023)

Detta projekt undersöker sambandet mellan globala CO₂-utsläpp och frekvensen av naturkatastrofer över tid. Analysen genomförs i `main.ipynb`, där data bearbetas, visualiseras och analyseras med fokus på långsiktiga trender.

Syftet är att se om ökande utsläpp kan kopplas till ökande klimatrelaterade naturkatastrofer.

---

## Innehåll i projektet

| Fil | Beskrivning |
|----|-------------|
| `main.ipynb` | Notebook som innehåller all analys, visualiseringar och slutsatser |
| `README.md` | Dokumentation och översikt av projektet |

Alla dataset och temporära filer exkluderas från Git genom `.gitignore`.

---

## Metoder och Bibliotek

Projektet använder:

| Bibliotek | Användning |
|----------|------------|
| `pandas` | Datainläsning och rensning |
| `numpy` | Numeriska operationer |
| `matplotlib` och `seaborn` | Visualisering av trender och samband |
| `scikit-learn` | Standardisering och PCA (Principal Component Analysis) |

---

## Analysens Upplägg

1. Data läses in och rensas
2. CO₂-utsläpp och antal naturkatastrofer sammanställs per år
3. Tidsserier visualiseras för att se utvecklingen över tid
4. Variabler standardiseras för att kunna jämföras på samma skala
5. PCA används för att undersöka vilka faktorer som påverkar variationen i datan
6. Resultat tolkas och slutsatser dras

---

## Resultat (Sammanfattning)

- CO₂-utsläppen visar en tydligt ökande trend över flera decennier.
- Antalet rapporterade naturkatastrofer ökar över samma tidsperiod.
- Trenderna pekar åt samma håll och tyder på ett samband.
- PCA-analysen visar att temperatur och utsläpp påverkar variationen i katastroffrekvens.

---

## Slutsats

Analysen stödjer hypotesen att ökande CO₂-utsläpp hänger ihop med ökande frekvens av naturkatastrofer. Resultaten är förenliga med rådande forskning kring klimatförändringar och extremväder.

---

## Körning

För att köra projektet:

