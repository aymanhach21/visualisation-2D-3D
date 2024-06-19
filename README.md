# Projet de Visualisation Géospatiale avec OpenLayers et Cesium

Ce projet combine OpenLayers et Cesium pour créer une application de visualisation géospatiale interactive en 2D et 3D. Il offre des fonctionnalités avancées telles que la mesure de distances, la visualisation des bâtiments en 3D, et l'intégration de couches GeoJSON et de maquettes 3D.

## Fonctionnalités

- **Mesure de Distance**: Cliquez sur deux points pour calculer et afficher la distance entre eux.
- **Visualisation 3D des Bâtiments**: Affichage des bâtiments en 3D avec la possibilité de mesurer leur hauteur.
- **Synchronisation des Vues**: La vue 3D de Cesium est synchronisée avec la carte 2D d'OpenLayers pour une transition fluide entre les deux perspectives.
- **Couches GeoJSON**: Intégration de couches GeoJSON pour la voirie et les bâtiments, affichées en 3D.
- **Maquette 3D**: Affichage d'une maquette 3D détaillée pour une visualisation encore plus immersive.
- **Carte d'Inondation**: Ajout d'une couche d'inondation pour une analyse environnementale.

## Technologies Utilisées

- [OpenLayers](https://openlayers.org/)
- [CesiumJS](https://cesium.com/cesiumjs/)
- JavaScript
- CSS

## Installation

1. Clonez ce dépôt :
    ```bash
    git clone https://github.com/votre-utilisateur/nom-du-repo.git
    ```

2. Naviguez dans le répertoire du projet :
    ```bash
    cd nom-du-repo
    ```

3. Ouvrez `index.html` dans votre navigateur préféré.

## Utilisation

### Mesurer des Distances

1. Cliquez sur le bouton "Measure Distance" pour activer le mode de mesure.
2. Cliquez sur deux points sur la carte pour mesurer la distance entre eux.
3. La distance calculée sera affichée en haut de la carte.

### Visualisation des Bâtiments en 3D

- Cliquez sur un bâtiment dans la vue 3D pour mesurer sa hauteur.

### Synchronisation des Vues

- La vue 2D d'OpenLayers est automatiquement synchronisée avec la vue 3D de Cesium pour une transition fluide entre les perspectives.


