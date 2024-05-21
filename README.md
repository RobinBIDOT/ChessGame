# ChessGame

## Description

L'application d'échecs propose deux modes de jeu : jouer contre un ami dans le même navigateur et jouer contre l'ordinateur, en utilisant l'API REST de Stockfish disponible sur https://stockfish.online/

## Fonctionnalités

- **Mode contre un ami** : Jouez contre un autre joueur sur le même appareil.
- **Mode contre l'ordinateur** : Affrontez l'ordinateur en utilisant l'API Stockfish pour générer les coups.
- **Promotion des pions** : Sélectionnez la pièce à promouvoir lorsque votre pion atteint la dernière rangée.
- **Castling (Roque)** : Effectuez un roque pour protéger votre roi.
- **Échec et Mat** : Le jeu détecte les situations d'échec et mat.
- **Son de mouvement** : Écoutez les sons des mouvements des pièces pour une expérience de jeu immersive.

## Installation

Suivez les étapes ci-dessous pour installer et exécuter l'application localement :

1. **Cloner le dépôt** :
    ```sh
    git clone https://github.com/RobinBIDOT/ChessGame.git
    cd votre-repo
    ```

2. **Installer les dépendances** :
    ```sh
    npm install rxjs

    npm install @angular/common

    npm install @angular/core

    npm install @angular/router

    npm install @angular/material @angular/cdk @angular/animations

    npm install @angular/common
    ```

3. **Exécuter l'application** :
    ```sh
    ng serve
    ```

4. **Accéder à l'application** :
   Ouvrez votre navigateur et rendez-vous sur `http://localhost:4200`.

## API utilisée

L'application utilise l'API Stockfish pour le mode contre l'ordinateur. L'API est accessible à l'adresse suivante : [Stockfish API](https://stockfish.online/).

## Images des pièces

Les images des pièces sont utilisées à partir du dépôt officiel de Lichess : [Lichess GitHub](https://github.com/lichess-org).

## Tutoriel

Un tutoriel détaillé pour créer cette application est disponible sur la chaîne YouTube de FreeCodeCamp : [Lien vers le tutoriel](https://youtu.be/fJIsqZmQVZQ).

---

Pour toute question ou demande d'assistance, n'hésitez pas à ouvrir une issue sur GitHub ou à me contacter directement.

Bon jeu ! 🎮♟️
