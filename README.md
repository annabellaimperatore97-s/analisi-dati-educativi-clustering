# Analisi dei Dati Complessi

## Descrizione del progetto

Questo repository contiene un progetto di analisi dei dati complessi realizzato in linguaggio **R** utilizzando **RStudio** e **Quarto** per la produzione di un report riproducibile.

L'obiettivo del progetto è esplorare e analizzare un dataset relativo al contesto educativo attraverso tecniche di analisi statistica multivariata. In particolare, il lavoro si concentra sull'identificazione di **strutture latenti nei dati**, ovvero schemi nascosti o gruppi di osservazioni con caratteristiche simili.

Il report integra codice, spiegazioni metodologiche, risultati e visualizzazioni grafiche, permettendo una comprensione completa dell'intero processo di analisi.

## Metodologia dell'analisi

L'analisi è stata articolata in diverse fasi principali:

### 1. Esplorazione preliminare dei dati

In una prima fase è stata effettuata un'analisi esplorativa del dataset per comprenderne la struttura, le variabili presenti e le eventuali relazioni tra di esse.
Sono state utilizzate statistiche descrittive e rappresentazioni grafiche per individuare pattern iniziali nei dati.

### 2. Analisi delle relazioni tra variabili

Successivamente sono state applicate tecniche di analisi multivariata per studiare le relazioni tra le variabili del dataset e ridurre la complessità dell'informazione contenuta nei dati.

Tra le tecniche utilizzate rientrano:

* **Analisi delle Corrispondenze Multiple (MCA)** per l'esplorazione di dati categoriali
* rappresentazioni grafiche nello spazio fattoriale
* analisi delle associazioni tra variabili e individui

### 3. Analisi di clustering

Per identificare gruppi omogenei di osservazioni sono stati applicati diversi metodi di clustering, con l'obiettivo di confrontarne i risultati e individuare eventuali strutture latenti nei dati.

In particolare sono stati utilizzati:

* **i-FCB**
* **Cluster CA**
* **K-means applicato alle coordinate MCA**

Il confronto tra questi metodi permette di valutare come diverse tecniche di clustering rappresentino la struttura del dataset e di individuare eventuali gruppi significativi.

### 4. Visualizzazione e interpretazione dei risultati

I risultati dell'analisi sono stati rappresentati tramite grafici e mappe fattoriali che permettono di visualizzare:

* la distribuzione degli individui nello spazio delle componenti principali
* la relazione tra variabili
* la struttura dei cluster identificati

Queste visualizzazioni facilitano l'interpretazione dei risultati e consentono di comprendere meglio le caratteristiche dei gruppi individuati.

## Strumenti utilizzati

Il progetto è stato sviluppato utilizzando i seguenti strumenti:

* R
* RStudio
* Quarto
* librerie R per analisi multivariata e visualizzazione dei dati

Quarto è stato utilizzato per integrare codice, testo e grafici all'interno di un unico documento riproducibile.

## Contenuto del repository

Il repository include i seguenti file principali:

* `.qmd` → file Quarto contenente il codice R e il testo del report
* `.html` → report finale generato dal documento Quarto
* eventuali dataset utilizzati nell'analisi 

## Come visualizzare il report

Il report finale è disponibile nel file `.html`.
A causa delle dimensioni del file, GitHub potrebbe non visualizzarlo direttamente nel browser.

Per visualizzare correttamente il report completo con tutti i grafici:

1. scaricare il file `.html` dal repository
2. aprirlo con un browser web (Chrome, Safari, Firefox, ecc.)

## Riproducibilità dell'analisi

Per riprodurre l'intera analisi:

1. scaricare o clonare il repository
2. aprire il file `.qmd` in RStudio
3. eseguire il rendering del documento tramite Quarto

Questo genererà automaticamente il report completo con tutte le analisi e visualizzazioni.

## Autore

Progetto realizzato da **Annabella Imperatore** nell'ambito di un lavoro universitario di analisi dei dati complessi.

