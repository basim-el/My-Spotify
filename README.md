# My-Spotify 🎧

## Sommaire

- [Aperçu](#aperçu)
- [Caractéristiques principales](#caractéristiques-principales)
- [Pré-requis](#pré-requis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [À propos de l'auteur](#à-propos-de-lauteur)

## Aperçu

**My-Spotify** est une application web développée en React, qui réplique certaines fonctionnalités de Spotify. L'application utilise l'API de Spotify pour permettre aux utilisateurs de consulter des listes de lecture, de rechercher des chansons, des albums et des artistes, ainsi que d'écouter des extraits de musique. Le projet est conçu pour offrir une expérience similaire à celle de la célèbre plateforme de streaming musical.

## Caractéristiques principales

- **Recherche de musique** : Les utilisateurs peuvent rechercher des artistes, des albums et des chansons grâce à des appels à l'API Spotify.
- **Lecture d'extraits musicaux** : Écoute d'extraits de chansons disponibles via l'API Spotify.
- **Interface utilisateur dynamique** : L'application est responsive et intègre une interface fluide, similaire à celle de Spotify, avec des animations et transitions.

## Pré-requis

- Node.js (version 14 ou plus recommandée)
- npm ou yarn
- Un accès à l'API Spotify (création d'une application sur [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/))

## Installation

1. Clonez le dépôt GitHub du projet :

    ```bash
    git clone https://github.com/basim-el/my-spotify.git
    ```

2. Rendez-vous dans le répertoire du projet :

    ```bash
    cd my-spotify
    ```

3. Installez les dépendances nécessaires avec npm ou yarn :

    ```bash
    npm install
    ```

    ou

    ```bash
    yarn install
    ```

4. Démarrez l'application de développement :

    ```bash
    npm start
    ```

    ou

    ```bash
    yarn start
    ```

5. Ouvrez votre navigateur et accédez à l'adresse `http://localhost:3000` pour voir l'application.

## Utilisation

### Fonctionnalités principales

- **Rechercher de la musique** : Utilisez la barre de recherche pour explorer les artistes, albums ou chansons disponibles sur Spotify.
- **Lecteur musical** : Cliquez sur une chanson pour écouter un extrait.

### Déploiement

Pour déployer l'application en production, assurez-vous de configurer correctement les variables d'environnement pour votre serveur d'hébergement et d'exécuter la commande suivante pour créer un build optimisé :

```bash
npm run build
```

Le dossier `build/` généré pourra ensuite être déployé sur n'importe quel service d'hébergement web.

## À propos de l'auteur

👤 **Basim El Sayed**

- [Portfolio](https://www.eldev.fr/)
- [LinkedIn](https://www.linkedin.com/in/basim-el-sayed/)
