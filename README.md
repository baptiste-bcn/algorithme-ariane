# SAE21_2022 : Algorithme d'Arianne

## Description du Projet
Ce projet est centré sur l'étude d'un algorithme de guidage inspiré par la mythologie grecque, aidant Thésée à naviguer à travers un labyrinthe pour trouver la sortie. Le but est de développer un programme en Java qui simule ce scénario dans une grille représentant le labyrinthe, avec des obstacles et un chemin vers la sortie.

## Commandes
- `make` : compile le projet.
- `make run` : compile le projet et lance le projet.
- `make clean` : supprime tous les fichiers liés à la compilation.

## Représentations dans le jeu
- `Thésée` est représenté par un carré rouge 🟥.
- `La sortie` est représentée par un carré vert 🟩.

## Principes de l'Algorithme
Thésée peut se déplacer dans le labyrinthe vers le nord, le sud, l'est, ou l'ouest. Les mouvements de Thésée sont déterminés par un algorithme qui prend en compte l'état actuel des cases (libre, bloquée, sortie).

## Format de Sauvegarde des Grilles
Les grilles sont sauvegardées sous un format spécifique où chaque bit représente l'état d'une case, et les premiers octets décrivent la taille de la grille et les positions de Thésée et de la sortie.

## Note du Projet
Nous avons obtenu la note de 12.50/20 lors de ce projet.

---

© Baptiste BLANCHON, Samet DURAN 
- [Sujet disponible ici](https://iut-fbleau.fr/sitebp/pt21/21_2022/STCL6EZD72IDTX73.php).