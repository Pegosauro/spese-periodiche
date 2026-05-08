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
7. Dopo qualche minuto GitHub genererà il link pubblico del sito.

## Uso su iPhone

1. Apri il link GitHub Pages da Safari.
2. Tocca **Condividi**.
3. Seleziona **Aggiungi alla schermata Home**.
4. Apri l’app dalla Home.

## Backup

I dati vengono salvati localmente nel browser.  
Usa periodicamente **Backup → Esporta file JSON** per salvare una copia su iCloud Drive.

## Nota importante

Se cancelli i dati di Safari o usi un altro browser/dispositivo, i dati locali potrebbero non essere disponibili.  
Il file JSON esportato è il metodo consigliato per conservare e trasferire i dati.
