# Art&Escrime

Site web statique (SAE, 1ʳᵉ année d'informatique) sur l'escrime aux Jeux de Paris 2024.

## Structure

```
index.html              Page d'accueil
pages/                  Autres pages du site
assets/
  css/
    base.css            Styles communs (reset, header/nav, hero, footer, responsive)
    pages/<page>.css    Styles propres à chaque page
  img/
    <page>/             Images propres à chaque page
```

## Conventions

- Noms de fichiers en minuscules, séparés par des tirets (`stats-nationales.html`).
- Chaque page charge `base.css` puis son fichier `assets/css/pages/<page>.css`.
- Ouvrir `index.html` dans un navigateur suffit, il n'y a pas d'étape de build.
