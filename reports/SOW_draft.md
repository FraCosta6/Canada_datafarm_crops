## Canada’s Fields in Time: 77 Years of Agricultural Trends (1908–1984)

Questo progetto si basa su un dataset storico rilasciato da Statistics Canada, contenente dati agricoli canadesi raccolti tra il 1908 e il 1984.  
Il file include 10.207 osservazioni e 9 variabili, relative a:

- Tipologie di colture seminate  
- Province e territori canadesi  
- Metriche economiche: prezzo medio e valore totale in dollari canadesi  
- Parametri agronomici: produzione (tonnellate), resa media (kg/ha), superficie coltivata (ha/acri)

Le colture monitorate includono varietà chiave per l’economia agricola del paese, come wheat, barley, oats, corn for grain, rye, flaxseed e molte altre.

## Obiettivo dell’analisi

L’obiettivo è analizzare l’evoluzione storica della produzione agricola in Canada, individuando trend, differenze geografiche e impatti economici.  
L’analisi si articola in cinque aree principali:

1. **Produzione agricola nel tempo**  
   Analisi dei volumi prodotti per coltura dal 1908 al 1984.

2. **Valore economico generato**  
   Studio dell’andamento del prezzo medio e del valore totale.

3. **Confronto tra province**  
   Analisi delle differenze regionali nella produttività.

4. **Efficienza agricola**  
   Valutazione di resa media e superficie coltivata per coltura.

5. **Scenario ipotetico futuro**  
   Proiezione teorica di alcune colture fino al 2024 o al 2034 sulla base dei trend storici.

L’intero lavoro è di tipo esplorativo e descrittivo.  
Si basa su analisi statistiche elementari, rappresentazioni grafiche, e costruzione narrativa supportata dai dati.  
Non vengono utilizzati modelli predittivi avanzati o algoritmi di machine learning.

## Scope / Major Project Activities

Le attività principali del progetto sono suddivise come segue:

### 1. Data Exploration and Understanding
- Caricamento e ispezione del dataset in formato CSV
- Esame della struttura, delle colonne e del contenuto
- Identificazione di valori mancanti

### 2. Data Cleaning and Preparation
- Trattamento dei valori nulli o incoerenti
- Eliminazione di record aggregati o codici non riconducibili a province esistenti
- Visualizzazione anomalie e outlier
- Esportare file CSV in data_clean

### 3. Analytical Breakdown (Key Study Axes)
- **Produzione nel tempo**: analisi delle quantità raccolte per ogni coltura e provincia
- **Valore economico**: studio dell’andamento del prezzo medio e del valore totale della produzione
- **Confronto geografico**: confronto tra province per produttività, valore e resa
- **Efficienza agricola**: analisi della resa media per ettaro e delle superfici coltivate
- **Proiezione teorica**: simulazione dell’andamento futuro di una o più colture sulla base dei trend storici

### 4. Visualizations and Dashboards
- Creazione di grafici temporali, heatmap, bar chart comparativi e scatter plot
- Esportazione di visualizzazioni su Google Sheets e Tableau (link forniti nel README)
- Inserimento degli screenshot significativi nella cartella `outputs`

### 5. Documentation and Reporting
- Redazione della documentazione tecnica e narrativa
- Strutturazione del progetto in cartelle logiche (`data_raw`, `notebooks`, `reports`, `outputs`)
- Pubblicazione del progetto su GitHub, con README completo e note metodologiche

### 6. Deliverables Finali
- Jupyter Notebook strutturato con codice + commenti
- Report in formato `.pdf` con visualizzazioni ed evidenze analitiche
- Link a dashboard esterne interattive (Tableau / Google Sheets)
- README.md con introduzione, obiettivi, metodologia, risultati e riflessioni finali
