# warehouse-cms

CMS per la gestione di magazzino, dove gli utenti possono:

Creare nuovi articoli di magazzino (nome, codice articolo, quantità, prezzo, fornitore, categoria)
Filtrare gli articoli in magazzino per nome, codice articolo, fornitore, categoria
Modificare i dettagli degli articoli di magazzino
Visualizzare un elenco di tutti gli articoli presenti in magazzino con dettagli
Gestire le categorie di articoli (creazione, modifica, eliminazione)
Gestire i fornitori (creazione, modifica, visualizzazione, eliminazione)
Dashboard Principale

Panoramica dell'inventario corrente
Widget per visualizzazioni rapide (es. articoli sotto una certa soglia di quantità, ultimi articoli aggiunti, etc.)
Gestione Articoli

Lista di tutti gli articoli con opzioni per filtrare per nome, codice articolo, fornitore, categoria
Form per la creazione di un nuovo articolo
Pagina di dettaglio per ogni articolo con opzione di modifica
Gestione Categorie

Lista delle categorie esistenti
Form per aggiungere una nuova categoria
Opzione per modificare o eliminare categorie esistenti
Gestione Fornitori

Lista dei fornitori con dettagli
Form per aggiungere un nuovo fornitore
Opzione per modificare o eliminare fornitori esistenti
Ricerca e Filtraggio

Funzionalità di ricerca avanzata integrata nelle pagine di gestione articoli, categorie e fornitori
Reportistica

Pagina per generare report personalizzati sull'inventario (es. movimentazione stock, articoli più venduti, ecc.)
Interazioni Utente nel CMS di Gestione Magazzino
Nell'utilizzare la Dashboard Principale:

L'utente può avere una visione immediata dello stato attuale del magazzino.
Può visualizzare widget per informazioni rapide, come gli articoli con scorte basse o gli ultimi aggiunti.
Nella Gestione degli Articoli:

L'utente può visualizzare un elenco di tutti gli articoli in magazzino con possibilità di filtrarli per vari criteri.
Può creare un nuovo articolo inserendo i dettagli richiesti nel form dedicato.
Per ogni articolo, può accedere alla pagina di dettaglio dove è possibile modificarne i dettagli o eliminarlo.
Nella Gestione delle Categorie:

L'utente può visualizzare un elenco di tutte le categorie esistenti.
Può aggiungere una nuova categoria utilizzando un form specifico.
Ha la possibilità di modificare o eliminare le categorie esistenti.
Nella Gestione dei Fornitori:

L'utente può vedere una lista di tutti i fornitori con dettagli correlati.
Può aggiungere un nuovo fornitore compilando un form.
Può modificare o eliminare le informazioni dei fornitori esistenti.
Utilizzando la Ricerca e il Filtraggio:

L'utente può effettuare ricerche avanzate all'interno delle pagine di gestione articoli, categorie e fornitori per trovare rapidamente ciò che cerca.
Nella Creazione di Reportistica:

L'utente può generare report personalizzati basati su diversi parametri del magazzino, come la movimentazione dello stock o gli articoli più venduti, per avere un'analisi dettagliata delle performance.
Dashboard Principale
Titolo: Dashboard
Feature:
Visualizzazione rapida dello stato attuale del magazzino.
Widget per informazioni immediate su:
Articoli con scorte basse.
Ultimi articoli aggiunti.
Riepilogo rapido di articoli per categoria.
Visualizzazione degli articoli più venduti/movimentati.
Gestione Articoli
Titolo: Gestione Articoli
Feature:
Visualizzazione di un elenco completo degli articoli in magazzino con opzioni di filtro per nome, codice articolo, fornitore, categoria.
Form per la creazione di un nuovo articolo di magazzino, includendo campi per nome, codice articolo, quantità, prezzo, fornitore, categoria.
Opzione per accedere alla pagina di dettaglio di ogni articolo, con possibilità di modifica dei dettagli o eliminazione dell'articolo.
Gestione Categorie
Titolo: Gestione Categorie
Feature:
Visualizzazione di un elenco di tutte le categorie esistenti.
Form per l'aggiunta di una nuova categoria, con campi per il nome della categoria.
Opzioni per modificare o eliminare categorie esistenti, facilitando la gestione e l'organizzazione delle categorie di articoli nel magazzino.
Gestione Fornitori
Titolo: Gestione Fornitori
Feature:
Visualizzazione di una lista completa dei fornitori con i dettagli correlati.
Form per l'aggiunta di un nuovo fornitore, includendo campi per il nome, contatto, e dettagli del fornitore.
Opzioni per modificare o eliminare i fornitori esistenti, permettendo una gestione efficiente delle relazioni con i fornitori.
Ricerca e Filtraggio
Titolo: Ricerca Avanzata
Feature:
Funzionalità di ricerca e filtraggio integrata nelle pagine di gestione articoli, categorie e fornitori.
Permette agli utenti di effettuare ricerche specifiche all'interno del magazzino utilizzando vari criteri come nome, codice articolo, fornitore, e categoria.
Include filtri avanzati per affinare le ricerche, migliorando l'efficienza nella localizzazione degli articoli o delle informazioni desiderate.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/warehouse-cms.git
cd warehouse-cms
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Tech stack

- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Chakra UI](https://chakra-ui.com/)

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
