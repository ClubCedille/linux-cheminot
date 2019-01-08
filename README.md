# linux-cheminot
Image docker pour utiliser [Cheminot](https://www.etsmtl.ca/Etudes/ChemiNot) facilement sous linux.

Cheminot est un programme permettant aux étudiants de l'ÉTS de s'inscrire/se désinscrire des cours.

## Dépendances

- Make
- Docker
- xorg-xhost

## Installation

Installer les dépendances et ensuite, cloner le dépôt.

## Utilisation

Pour lancer Cheminot, exécuter

```

cd linux-cheminot

make run

```

_La commande `make` peut nécessiter les droits de super-utilisateur puisqu'elle fait utilisation de docker._

## Repository original

https://github.com/aviau/linux-cheminot
