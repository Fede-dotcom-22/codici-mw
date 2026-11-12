# Codici MW 2.0 — responsive

Caricare **tutti i file e cartelle contenuti** in questa cartella nella radice del repository GitHub Pages. Sostituire i file esistenti quando richiesto.

## Interfaccia
- Desktop: barra laterale, ricerca ampia, griglia 2–3 colonne.
- Smartphone: navigazione inferiore, categorie scorrevoli, schede a colonna singola.
- Tablet: layout intermedio.
- Icone ricavate dall'immagine originale fornita dall'utente (sorgente molto piccola: qualità limitata).
- Le fotografie dei prodotti sono mostrate se il campo `image` contiene un URL valido; nessuna foto è inventata o aggiunta al catalogo dimostrativo.
- I marchi sono rappresentati da etichette testuali, non da loghi ufficiali.

## Aggiunta manuale
Aprire `admin/`, compilare il modulo, scaricare `catalogo.json` e sostituirlo su GitHub. La pagina admin è pubblica, ma non ha accesso di scrittura al repository. Evitare modifiche concorrenti: scaricare sempre dal catalogo aggiornato prima di aggiungere una variante.

## Limitazioni
Catalogo dimostrativo: un modello e due PIM. Non importare dati del collega senza autorizzazione. Nessuno scraping automatico. Non è implementato un sistema di autenticazione admin né la sincronizzazione offline.
