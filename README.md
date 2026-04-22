# Portfolio de Tajdin Acar

Portfolio statique prêt à être publié sur **GitHub Pages**.

## Structure

- `index.html`
- `styles.css`
- `script.js`

## Mise en ligne sur GitHub Pages

### Option simple
1. Crée un repository GitHub, par exemple `tajdin-portfolio`.
2. Dépose les 3 fichiers à la racine du repository.
3. Va dans **Settings > Pages**.
4. Dans **Build and deployment**, choisis:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `/root`
5. Enregistre.
6. Ton site sera publié sur une URL de type :
   `https://ton-identifiant.github.io/tajdin-portfolio/`

## Personnalisation rapide

### Modifier les informations de contact
Dans `index.html`, cherche :
- `tajdinacar@icloud.com`
- `+33 7 82 99 21 64`
- le lien LinkedIn

### Ajouter ton CV en téléchargement
1. Ajoute ton CV PDF dans le repository, par exemple `cv-tajdin-acar.pdf`
2. Dans la section hero ou contact, ajoute un bouton :

```html
<a class="btn btn-secondary" href="cv-tajdin-acar.pdf" target="_blank">Télécharger mon CV</a>
```

### Ajouter une photo
Tu peux remplacer le bloc `TA` dans la carte de droite par une image.

## Recommandation pour les candidatures
Tu peux mettre dans ton CV ou dans tes mails de candidature :
**Portfolio :** `https://ton-identifiant.github.io/tajdin-portfolio/`

