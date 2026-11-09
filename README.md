# F1 Manager 2026

Jeu de management de Formule 1 jouable dans le navigateur (HTML/CSS/JS, aucun outil de build).

## Publier sur GitHub Pages
1. Crée un dépôt GitHub, puis envoie le contenu de ce dossier à la racine (index.html, .nojekyll, README.md).
2. Dépôt > Settings > Pages > Source : "Deploy from a branch", branche `main`, dossier `/ (root)`.
3. Après une minute, le jeu est en ligne sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Données
Écuries, pilotes, numéros, nationalités, circuits et calendrier : saison 2026.
Statistiques des pilotes, niveaux des voitures et durées de tour : estimations du jeu, non officielles.

## Tracés des circuits
La carte de course charge les vrais tracés (fichiers GeoJSON) du dépôt https://github.com/bacinger/f1-circuits (licence MIT, données non officielles) au premier lancement, puis les garde en cache dans le navigateur. Il faut donc une connexion internet au premier lancement. Sans connexion, le jeu affiche des tracés schématiques de secours.
