# Codici MW 2.0

PWA gratuita per cercare rapidamente i codici PIM MediaWorld a sei cifre di smartphone, smartwatch, sportwatch e smartband.

## Installazione su GitHub Pages

Carica **il contenuto** di questa cartella nella radice del repository `codici-mw` (non la cartella contenitore). In Settings > Pages scegli Deploy from a branch, main, /(root).

## Catalogo

`catalogo.json` contiene un modello dimostrativo con due varianti PIM. Verificare i dati prima dell'uso operativo. Per aggiungere una variante aprire `admin/`, compilare il modulo e scaricare `catalogo.json`, poi sostituire il file nel repository con un commit. **La pagina admin è pubblica e non richiede autenticazione: non scrive sul repository, ma prepara solo un file locale.** Solo chi ha i permessi GitHub può pubblicare.

## Immagini e marchi

L'interfaccia prevede un campo `image` per ogni modello: usare soltanto URL o immagini per cui si possiedono i diritti di utilizzo. In mancanza di foto compare un segnaposto elegante. I marchi sono visualizzati come nomi testuali, senza loghi non autorizzati. L'icona dell'app deriva dall'immagine fornita dall'utente (originale di piccole dimensioni: potrebbe risultare poco nitida su schermi ad alta risoluzione).

## Limiti

Nessuno scraping e nessuna ricerca automatica di nuovi PIM. La sincronizzazione è la lettura del JSON pubblicato, non un database con scrittura diretta. Non caricare dati del collega senza autorizzazione. L'importazione manuale è a una variante per volta; per più varianti ripetere il processo dopo aver pubblicato la precedente o usare un futuro editor multi-variante.
