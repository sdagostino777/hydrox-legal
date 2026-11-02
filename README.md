# hydrox-legal

Pagine legali e di assistenza di **Hydrox**, pubblicate con GitHub Pages.

- `index.html` — assistenza (italiano); `index.en.html`, `index.es.html`, `index.de.html`, `index.fr.html` le altre lingue
- `privacy.html`, `termini.html`, `avvertenza.html` (+ versioni `.en`, `.es`, `.de`, `.fr`)
- `privacy.html` è l'URL che App Store Connect usa per l'informativa sulla privacy: si apre senza sapere la lingua

Le pagine non si scrivono qui a mano: si generano con
`python3 Scripts/genera-pagine-legali.py` dentro il progetto dell'app, dagli stessi
testi che sono nell'app. Se cambia una clausola, si rigenerano e si ricopiano.
