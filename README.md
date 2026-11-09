# F1 Manager 2026

Jeu de management de Formule 1 dans le navigateur (HTML/CSS/JS, zéro build).

## Interface
Dashboard sombre type F1 : barre latérale, progression de saison, cartes animées, confettis podium, sons optionnels.

## Fonctionnalités utiles ajoutées
- Comparaison de ta voiture vs les rivaux
- Historique des derniers GP (positions / points)
- Conseil stratégie avant chaque course (selon circuit & météo)
- Astuces coach aléatoires
- Barre de progression de saison
- Sons (clic, upgrade, podium) — activables dans le QG
- Confettis si podium
- Raccourcis clavier : `G` = aller au GP, `1–5` = onglets QG
- Légende pneus + tip composé

## Publier sur GitHub Pages
1. Envoie index.html, .nojekyll, README.md à la racine d’un dépôt.
2. Settings > Pages > Deploy from branch `main` / root.
3. Le jeu est en ligne sur `https://TON-PSEUDO.github.io/NOM-DU-DEPOT/`.

## Données
Écuries, pilotes, circuits, calendrier : saison 2026 (estimations non officielles pour les stats).
Tracés réels chargés depuis bacinger/f1-circuits (MIT) au premier lancement, puis mis en cache.
