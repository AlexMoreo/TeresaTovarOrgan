# TeresaTovarOrgan

Sito web di Teresa Tovar — pianista e organista a Pisa (Le Piagge). Lezioni di pianoforte per bambini e adulti, servizi d'organo per matrimoni, funerali e battesimi.

Realizzato con [Jekyll](https://jekyllrb.com/) e il tema [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/), pubblicato su GitHub Pages.

## Sviluppo locale

```bash
bundle install
bundle exec jekyll serve
```

## Da fare prima della pubblicazione

- [ ] Sostituire le immagini placeholder in `assets/images/` (hero.jpg, piano-feature.jpg, organ-feature.jpg) con foto reali
- [ ] Impostare `YOUR_FORM_ID` in `_pages/contact.md` con l'ID del form creato su [Formspree](https://formspree.io) (piano gratuito: 50 invii/mese)
- [ ] Aggiungere l'email di contatto in `_config.yml` (campo `author.email`)
- [ ] Abilitare GitHub Pages: Settings → Pages → Source → Deploy from a branch → `master` / `(root)`
