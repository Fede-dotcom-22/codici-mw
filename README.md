# Codici MW 2.0 — UI Gemini integrata

Interfaccia basata sul prototipo HTML approvato. `index.html` è la nuova applicazione; `catalogo.json` contiene i soli PIM ufficialmente inseriti.

- Nessun codice PIM dimostrativo viene caricato.
- Ricerca, categorie, navigazione, memoria, copia, preferiti e tema sono nell’interfaccia.
- I preferiti e gli inserimenti manuali sono salvati nel localStorage del browser, non condivisi con altri dispositivi.
- Per pubblicare aggiunte condivise usare `/admin/` ed effettuare il commit del `catalogo.json` scaricato.
- Il prototipo utilizza Tailwind CSS via CDN e Google Fonts; richiede una connessione internet per gli stili e i font. Per una futura release offline, compilare Tailwind localmente.
- I disegni dei dispositivi sono illustrazioni SVG, non fotografie ufficiali.

Pubblicazione: caricare il contenuto di questa cartella nella root del repository GitHub Pages.
