# Titanic Data Explorer

Mini progetto di data analysis su dataset open (Titanic), svolto come esercizio settimanale
per consolidare le basi di analisi dei dati con Python e Pandas. giuseppe

## Obiettivo
Esplorare un dataset reale, valutarne la qualità e svolgere un’analisi descrittiva
focalizzata su età, classe del biglietto e sopravvivenza.

## Dataset
Il dataset originale `titanic.csv` (open data) non è incluso nella repository.

Per riprodurre il progetto:
1. scaricare un dataset Titanic in formato CSV
2. salvarlo come `raw/titanic.csv`
3. eseguire il notebook `titanic_explorer.ipynb`

Il dataset pulito è disponibile in:
`processed/titanic_clean.csv`

## Attività svolte
- Esplorazione iniziale del dataset (`head`, `info`)
- Analisi dei valori mancanti
- Gestione dei NaN:
  - `Age` → imputazione con la mediana
  - `Cabin` → creazione della feature `HasCabin`
- Creazione della variabile `FasciaEta`
- Analisi descrittiva della sopravvivenza:
  - per classe
  - per fascia d’età
  - analisi con conteggi (N) e percentuali

## Insight principali
- La classe del biglietto è il fattore più fortemente associato alla sopravvivenza
- L’età introduce variazioni, ma non annulla l’effetto della classe
- L’assenza di informazioni sulla cabina non è casuale e riflette differenze di classe

## Note
Progetto didattico svolto con approccio da data analyst junior, con attenzione
all’interpretazione critica dei dati e ai limiti del dataset.
