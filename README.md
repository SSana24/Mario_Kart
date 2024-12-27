# Mario Kart - Algorithme de Lee

Bienvenue dans **Mario Kart - Algorithme de Lee** ! Ce projet consiste à trouver le chemin le plus court dans un labyrinthe, en utilisant l'algorithme de Lee, une méthode classique de recherche de chemin dans un graphe.

## Description du Projet
L'objectif est de réaliser un programme capable de trouver le chemin le plus court entre deux points d'une carte modélisée en graphe.

### Fonctionnalités Principales
- **Parsing de la carte** : Lecture de la carte depuis un fichier passé en paramètre.
- **Modélisation** : Conversion de la carte en un graphe.
- **Algorithme de Lee** : Parcours du graphe pour déterminer le chemin le plus court.
- **Affichage du résultat** : Impression du chemin sous forme de coordonnées `y:x`.

### Exemple de Carte
```
  oo..E
  o..o.
  .o..o
  .So..
  .....
```

#### Légende :
- **`.`** : Point traversable
- **`o`** : Obstacle
- **`S`** : Point de départ
- **`E`** : Point d'arrivée

### Contraintes de Déplacement
- Déplacement uniquement **Haut, Bas, Gauche, Droite**.
- Pas de déplacement diagonal.

---

## Exécution du Programme
1. **Compiler et exécuter** :
   ```bash
   tsc main.ts
   node main.js map.txt
   ```
2. **Format de sortie** :
   ```
   y:x y:x y:x
   ```
   Exemple :
   ```
   3:1 4:1 4:2 4:3 3:3 2:3 2:2 1:2 0:2 0:3 0:4
   ```

---

## Format du Fichier Carte
Chaque fichier carte suit cette structure :
```
oo..E
o..o.
.o..o
.So..
.....
```
Le point en haut à gauche représente les coordonnées **0:0**.

---

## Contribuer
Les contributions sont les bienvenues ! Si vous souhaitez ajouter des fonctionnalités ou optimiser l'algorithme, n'hésitez pas à ouvrir une **pull request**.

---

## Licence MIT
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer. Consultez le texte complet de la licence ici :
[Licence MIT (anglais)](https://opensource.org/licenses/MIT)

---

Amusez-vous bien à coder et explorer des labyrinthes ! 🚀

