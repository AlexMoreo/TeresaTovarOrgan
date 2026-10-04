# TeresaTovarOrgan

Sito web di Teresa Tovar — pianista e organista a Pisa (Le Piagge). Lezioni di pianoforte per bambini e adulti, servizi d'organo per matrimoni, funerali e battesimi.

Realizzato con [Jekyll](https://jekyllrb.com/) e il tema [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), pubblicato su GitHub Pages.

## Sviluppo locale

```bash
bundle install
bundle exec jekyll serve
```

## Da fare prima della pubblicazione

- [ ] Sostituire le immagini placeholder in `assets/images/` (hero.jpg, piano-feature.jpg, organ-feature.jpg, concert-feature.jpg) con foto reali
- [x] Impostare l'ID del form di [Formspree](https://formspree.io) in `_pages/contact.md` (piano gratuito: 50 invii/mese)
- [x] Aggiungere l'email di contatto in `_config.yml` (campo `author.email`)
- [x] Abilitare GitHub Pages: Settings → Pages → Source → Deploy from a branch → `master` / `(root)`
- [ ] Confermare l'indirizzo email su Formspree cliccando il link ricevuto al primo invio del modulo
- [ ] Aggiornare la sezione "Prossimi concerti" in `_pages/concerts.md` con date reali
