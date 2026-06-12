# ANALISI DEMOGRAFICA EUROPEA

# Invecchiamento Demografico e Pressione sul Sistema Sanitario in Europa

## Descrizione
Analisi end-to-end dell'invecchiamento demografico nei principali paesi europei e del suo impatto sui sistemi sanitari nazionali. Il progetto copre l'intero flusso di lavoro analitico: dalla raccolta dei dati grezzi fino a una dashboard interattiva.

## Strumenti utilizzati
- **Python** — acquisizione dati via API, pulizia, analisi e visualizzazione
- **SQL / SQLite** — database relazionale, query analitiche e viste
- **Power BI** — dashboard interattiva a 4 pagine
- **DBeaver** — gestione e interrogazione del database

## Dataset
Dati World Bank Open Data API (2000-2022) per 16 paesi UE:
- Popolazione over 65 (% sul totale)
- Aspettativa di vita alla nascita
- Spesa sanitaria pro capite (USD)

## Analisi condotte
1. Ranking demografico europeo 2022
2. Correlazione spesa sanitaria / aspettativa di vita
3. Indice di efficienza sanitaria per paese
4. Velocità di invecchiamento 2000-2022
5. Proiezioni demografiche 2032-2042

## Principali insight
- L'Italia è la più anziana d'Europa ma con invecchiamento in rallentamento
- Finlandia e Polonia stanno invecchiando il doppio più velocemente dell'Italia
- Oltre una certa soglia di spesa, la correlazione con la longevità si indebolisce significativamente

## Struttura del progetto
portfolio_demografico/

├── data/

│   ├── raw/          # Dati originali scaricati via API

│   └── processed/    # Dataset puliti per Power BI

├── outputs/

│   ├── charts/       # Grafici Python

│   └── sql/          # Query SQL e database

├── demographic_health_analysis.ipynb

├── queries.txt

└── report_portfolio_demografico.md

## Contatti
[LinkedIn](#) | [GitHub](https://github.com/Mariano-Sassi)
