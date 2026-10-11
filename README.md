# CITISTATS — Visualiseur GeoJSON gratuit

Un mini-outil libre pour **afficher un GeoJSON sur une carte interactive**, explorer ses propriétés et coloriser les zones selon un champ numérique.

**[Essayer la démonstration](https://citicasarl.github.io/citistats-cartographe/)** · **[Découvrir CITISTATS CARTO](https://www.citistats.fr/cartographe/)**

## Fonctionnalités

- Import local `.geojson` ou `.json` (10 Mo maximum)
- Affichage de points, lignes et polygones avec Leaflet
- Popups avec les propriétés des objets
- Coloration graduée d'après un attribut numérique
- Couleur et opacité personnalisables
- Exemple intégré, sans téléchargement
- Aucun envoi du GeoJSON à un serveur

## Installation

Déposer `index.html` à la racine du dépôt GitHub. Dans **Settings → Pages**, sélectionner **Deploy from a branch**, puis `main` et `/ (root)`.

L'application fonctionne sans serveur, mais utilise Leaflet depuis un CDN et les tuiles OpenStreetMap en ligne.

## Limites

Ce visualiseur est une démonstration simple, pas un SIG complet. Pour composer des cartes, utiliser des fonds et données statistiques, découvrir **[CITISTATS CARTO](https://www.citistats.fr/cartographe/)**.

## Licence

MIT — voir `LICENSE`. Le code de la plateforme commerciale CITISTATS CARTO n'est pas inclus.
