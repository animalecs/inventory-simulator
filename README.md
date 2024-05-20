# Simulatore di Inventario

## Descrizione del Progetto

Questo progetto è stato sviluppato nel tempo libero per simulare l'evoluzione delle scorte di un prodotto in base a diversi parametri. Si tratta della prima versione e non è destinata all'uso in produzione. L'obiettivo principale è testare come il livello di servizio cambia in diverse condizioni variando i parametri della funzione `simulate_inventory`.

## Istruzioni per l'Installazione

L'intero codice è progettato per funzionare su Google Colab. È necessario solo un account Google per iniziare.

## Guida all'Uso

1. **Aprire Google Colab**: Vai su [Google Colab](https://colab.research.google.com/) e accedi con il tuo account Google.
2. **Caricare il file**: Carica il file `inventory_simulation.py` su Colab.
3. **Eseguire il codice**: Esegui le celle di codice in sequenza per simulare l'inventario.
4. **Modificare i parametri**: Nella funzione `simulate_inventory`, modifica i parametri per testare diverse condizioni di inventario.

## Parametri del file `simulate_inventory`

Ecco una descrizione dei parametri della funzione `simulate_inventory` e come influenzano la simulazione:

- **time_series (pd.Series)**: Serie temporale dei dati di domanda.
- **initial_weeks (int)**: Numero di settimane utilizzate per calcolare i parametri iniziali.
- **review_period (int)**: Periodo di tempo tra le revisioni dell'inventario.
- **lead_time (int)**: Tempo di consegna degli ordini.
- **service_level_z (float)**: Punteggio Z per il livello di servizio desiderato.
- **min_order (int, opzionale)**: Quantità minima d'ordine. Valore predefinito è 0.
- **ignore_pending_orders (bool, opzionale)**: Se ignorare o meno gli ordini in sospeso nei calcoli. Valore predefinito è False.
- **stochastic_lead_time (bool, opzionale)**: Se simulare un tempo di consegna stocastico o deterministico. Valore predefinito è False.
- **plot_simulation (bool, opzionale)**: Se visualizzare o meno i risultati della simulazione. Valore predefinito è False.
- **seed (int, opzionale)**: Seed per la generazione di numeri casuali. Valore predefinito è 42.

## Obiettivo del Progetto

L'obiettivo principale di questo progetto è testare come il livello di servizio vari in diverse condizioni variando i parametri della funzione `simulate_inventory`. Questo permette di analizzare le variazioni di stock e i potenziali stockout.

## Note Importanti

Questo progetto è nella sua prima versione e non è destinato all'uso in produzione. I feedback sono benvenuti per migliorare e aggiungere nuove funzionalità.

## Contatti

Per eventuali domande o feedback, puoi contattarmi all'indirizzo email: alexmina96@gmail.com

## Licenza

Questo progetto è concesso in licenza sotto i termini della Licenza MIT. Vedi il file `LICENSE` per i dettagli.
