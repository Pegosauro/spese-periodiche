# Spese Periodiche

Sito HTML/PWA semplice per iPhone per gestire spese periodiche, categorie e backup JSON.

## Funzioni

- Dashboard con totale mensile e annuale
- Gestione spese periodiche
- Categorie personalizzabili con colore
- Ricerca e filtro per categoria
- Prossimi rinnovi
- Spese attive/disattive
- Importazione dati da file JSON
- Esportazione backup JSON
- Salvataggio automatico nel browser tramite `localStorage`
- Tema chiaro/scuro
- Layout ottimizzato per iPhone

## Versione 1.1

Modifiche:
- Il widget **Spesa per categoria** è stato spostato sopra **Prossimi rinnovi**.
- Il widget **Spesa per categoria** è cliccabile.
- A ogni tap cambia periodo di calcolo:
  - giorno
  - settimana
  - mese
  - anno

## Struttura repository

```text
spese-periodiche/
├── index.html
├── manifest.json
├── assets/
│   └── icon.svg
├── .nojekyll
└── README.md
```

## Pubblicazione su GitHub Pages

1. Crea una nuova repository su GitHub.
2. Carica tutti i file contenuti in questa cartella.
3. Vai in **Settings** della repository.
4. Apri **Pages**.
5. In **Build and deployment**, scegli:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Salva.

## Uso su iPhone

1. Apri il link GitHub Pages da Safari.
2. Tocca **Condividi**.
3. Seleziona **Aggiungi alla schermata Home**.
4. Apri l’app dalla Home.

## Backup

I dati vengono salvati localmente nel browser.  
Usa periodicamente **Backup → Esporta file JSON** per salvare una copia su iCloud Drive.


## Versione 1.2

Modifiche:
- Header superiore fisso: lo scroll avviene solo nell'area contenuto.
- Modale inserimento spesa più compatta.
- Pulsanti della modale sempre visibili in basso.
- Campi data e select ottimizzati per iPhone.
- Selettore colore categoria reso visibile come anteprima colore.
