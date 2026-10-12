# Découvrir le Cartographe CITISTATS

Page de présentation interactive du **[Cartographe CITISTATS](https://citistats.fr/cartographe/carte/?utm_source=github&utm_medium=readme&utm_campaign=decouverte-cartographe)**, l'outil de cartographie en ligne gratuit et sans installation.

👉 **Voir la page :** https://github.com/citicasarl/citistats-cartographe/tree/main/demonstrateur_cartographe

## Au programme

- **Démo interactive** : changez de fond (plan, relief, satellite), choisissez un département et ajoutez d'un clic les contours des communes, la densité de population (carte choroplèthe) et la population (cercles proportionnels). Cliquez sur la carte pour tracer jusqu'à 3 isodistances et compter communes et habitants dans chaque zone. La légende se construit automatiquement.
- **Les 7 familles de calques** : fonds, territoires, zones, formes, textes, flèches, icônes
- **Les fonctionnalités** : isochrones, isodistances, zone commune, import d'adresses et de données CSV, indicateurs intégrés, dessin et mesures, export et partage
- **Gratuit sans compte / avec compte gratuit**

## Données et fonds de carte

- Contours et populations des communes : [API Géo](https://geo.api.gouv.fr) (données publiques)
- Fonds : OpenStreetMap, OpenTopoMap, Esri World Imagery
- Bibliothèque cartographique : [Leaflet](https://leafletjs.com)

## Technique

Un seul fichier HTML ; seule dépendance, Leaflet chargé depuis cdnjs. Les couleurs se règlent dans les variables `:root`.

## Licence

MIT
