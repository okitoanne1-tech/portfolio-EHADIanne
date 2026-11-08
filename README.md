# Portfolio — Anne Okito

Site statique (HTML / CSS / JS) : aucune installation, aucun build.

## Modifier le contenu
- **Textes, projets, expériences, certifications** → `index.html` (chaque section est commentée).
- **Couleurs** → variables en haut de `style.css` (`--accent` terracotta, `--digi` turquoise du numérique).
- **Mettre un mot en couleur ou en gras** → dans `index.html`, entoure-le de :
  - `<strong>mot</strong>` → gras
  - `<span class="hl">mot</span>` → terracotta surligné
  - `<span class="hl2">mot</span>` → turquoise surligné (numérique)
- **Photos** → dossier `assets/` (remplace un fichier en gardant le même nom).
- **Réseaux sociaux** → bas de `index.html` : remplace les liens LinkedIn et Instagram par les tiens.

## Publier
1. Dépose les fichiers à la racine d'un dépôt GitHub (`index.html`, `style.css`, `script.js`, `vercel.json`, dossier `assets`).
2. Sur vercel.com : *Add New → Project* → importe le dépôt → *Deploy* (Preset : Other).
3. Chaque modification sur GitHub redéploie le site automatiquement.
