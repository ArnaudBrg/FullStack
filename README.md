# Projet FullStack 

## Configuration Requise

- [Java](https://www.oracle.com/java/technologies/javase-downloads.html) (version recommandée: 11)
- [Node.js](https://nodejs.org/) (version recommandée: 14)
- [Angular CLI](https://cli.angular.io/) (pour le développement frontend)
- [Gradle](https://gradle.org/install/) (pour le développement backend)

## Installation

1. Clonez le dépôt GitHub :

    ```bash
    git clone https://github.com/ArnaudBrg/FullStack.git
    cd FullStack
    ```

2. Backend (API) :

    - Accédez au dossier `covid.api` :

        ```bash
        cd covid.api
        ```

    - Lancez le backend avec Gradle :

        ```bash
        gradle bootRun
        ```

        Le serveur backend sera accessible à l'adresse `http://localhost:5432`.

3. Frontend :

    - Accédez au dossier `Centre_Vaccination` :

        ```bash
        cd Centre_Vaccination
        ```

    - Installez les dépendances Node.js :

        ```bash
        npm install
        ```

    - Lancez le frontend avec Angular CLI :

        ```bash
        ng serve
        ```

        Le frontend sera accessible à l'adresse `http://localhost:4200`.

## Utilisation

Une fois les étapes d'installation complétées, ouvrez votre navigateur web et accédez à l'adresse `http://localhost:4200` pour utiliser l'application.
