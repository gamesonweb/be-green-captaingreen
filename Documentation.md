# Documentation

Ce fichier va présenter l'organisation du projet au niveau du code.

## Front

Le dossier /public et /dist contiennent les fichiers HTML qui permettent l'affiche et le lancement de l'application.

## Application TypeScript

Le dossier /src contient le code source de l'application :
- app.ts : Contient la gestion générale du jeu, avec la création et l'initialisation des objects en mémoire, des controlleurs des évènements. Il y a également la gestion de la machine à état car notre jeu se base sur ce pattern nous avons : en jeu, perdu, gagné, main screen.
- characterController.ts : Contient tout les définitions du personnage, avec sa caméra, sa physique et ces ressources.
- environnement.ts : Contient le chargement du décors
- inputController.ts : Contient l'implémentation des intéractions avec le joueur.