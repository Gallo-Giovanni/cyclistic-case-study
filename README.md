# Cyclistic Case Study

Questo progetto contiene l'analisi di un caso studio svolto durante il corso **Google Data Analytics**.

## Obiettivo

L'obiettivo del caso studio è capire in che modo i **casual rider** e i **membri annuali** utilizzano le bici Cyclistic in modo diverso, al fine di supportare strategie di marketing mirate alla conversione.

Il progetto segue il framework di analisi **Ask → Prepare → Process → Analyze → Share → Act**.

## Contenuto del repository

- `cyclistic_case_study.ipynb` → notebook Jupyter con tutto il codice dell'analisi
- `cyclistic_presentazione_v5.pptx` → presentazione del progetto (vedi sezione sotto)
- `Case Study 1_ How does a bike-share navigate speedy success.pdf` → traccia originale del corso

## Librerie principali

- Pandas
- NumPy
- Matplotlib
- Plotly Express

## Attività svolte

- Importazione e unione di 12 file CSV mensili (~5.8M righe)
- Pulizia del dataset: rimozione duplicati, valori negativi e outlier (<10 sec, >3 ore)
- Analisi esplorativa per giorno della settimana, mese, durata e tipo di bici
- Confronto sistematico casual vs member
- Produzione di visualizzazioni e raccomandazioni di business

## Presentazione

Il file `cyclistic_presentazione_v5.pptx` contiene una presentazione strutturata del progetto, pensata per un pubblico di business (es. portfolio LinkedIn).

Include:
- Business Task e contesto
- Valutazione delle fonti dati (criterio ROCCC)
- Documentazione del processo di cleaning
- Grafici fedeli a quelli prodotti nel notebook
- Conclusioni e raccomandazioni

> ⚠️ **Nota sulla presentazione:** i grafici nella presentazione utilizzano gli stessi dati e la stessa struttura del notebook. I valori numerici sono stati verificati direttamente dagli output del codice. La slide sul tipo di bici riporta la tabella `rideable_summary` con i dati reali.

## Nota sui dati

I file CSV originali non sono stati caricati nel repository a causa delle loro dimensioni elevate.  
Il dataset completo contiene circa **5.8 milioni di righe** ed è stato utilizzato per svolgere l'analisi descritta nel notebook. I dati sono pubblici e disponibili su [Divvy Bikes](https://divvybikes.com/system-data) sotto licenza Motivate International Inc.

## Nota finale

Questo progetto è stato realizzato come esercizio pratico di apprendimento e come parte della costruzione del mio portfolio in Data Analytics.
