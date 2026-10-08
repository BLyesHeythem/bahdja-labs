# Bahdja Labs

Site vitrine officiel de Bahdja Labs : agents IA, automatisation métier et produits technologiques.

Le site est disponible en français, anglais et arabe. La langue choisie est mémorisée dans le navigateur et l’interface passe automatiquement en lecture droite-à-gauche pour l’arabe.

## Prévisualisation locale

Avec Python :

```powershell
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Publication GitHub Pages

Le site est entièrement statique et peut être publié directement depuis la branche `main`, sans compilation.

Dans GitHub, ouvrir **Settings → Pages**. Dans **Build and deployment**, choisir **Deploy from a branch**, puis sélectionner la branche **main** et le dossier **/(root)**. Le site sera disponible à l’adresse :

`https://blyesheythem.github.io/bahdja-labs/`

## Structure

- `index.html` : contenu et structure de la page
- `styles.css` : identité visuelle et responsive
- `script.js` : navigation et animations légères
- `assets/` : logo et illustration

## Contact

Les boutons de contact ouvrent un nouveau message vers les deux contacts Bahdja Labs. Les adresses ne sont pas affichées directement dans le HTML afin de limiter la collecte par les robots simples.
