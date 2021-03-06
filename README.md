# RTv1

Troisième projet de la branche graphique en parallèle de wolf3d de l'école 42. Créer un programme qui utilise la méthode du 
raytracing.

Pour ce projet, quelques notions de base sont demandées et obligatoires :
* Gérer 4 formes géométriques basiques (sphère, plan, cône, cylindre)
* Gérer les translations et rotations
* Gérer le positionnement et la direction de la caméra
* Gérer la lumière (1 spot lumineux minimum) et les effets qu'elle implique (luminosité et ombre)

Enfin, voici les bonus qui peuvent être implémenter dans le programme :
* Multi-spot
* Brillance (Phong)

## Pour commencer

Ces instructions vous aideront à avoir une copie du projet et de pouvoir le faire marcher sur votre ordinateur.

### Prérequis

**Attention: A partir de maintenant, toutes les étapes (téléchargement, installation/compilation, exécution) seront à effectuer sur un terminal.**

#### Système d'exploitation

```
macOS Sierra
```

#### Téléchargement

Ce que vous devez faire pour télécharger les fichiers sources afin de pouvoir les compiler par la suite

```
git clone https://github.com/dcooray42/RTv1.git [nom du PATH/dossier]
```

### Installation

Se placer dans le dossier dans lequel vous avez fait la copie des fichiers sources du projet puis rentrer la commande suivante

```
make
```

Plusieurs fichiers .o auront fait leur apparitions dans le dossier que vous avez cloné ainsi que le binaire

```
rtv1
```

### Suppression

Pour supprimer les fichiers objets .o généré lors de la création du programme

```
make clean
```

Pour supprimer les fichiers objets .o et le programme

```
make fclean
```

Pour tout supprimer puis recompiler le programme

```
make re
```

## Faire des tests

Une fois que le programme a été créé, vous n'avez plus qu'à rentrer en ligne de commande le nom du programme + le fichier 
de description de scène.

### Utilisation du programme

Ligne de commande

```
./rtv1 [PATH/fichier de description de scène]
```

### Commandes

Utiliser la deuxième fenêtre ouverte simultanément avec la fenêtre de rendu de la scène pour interagir avec cette dernière.

#### Exemple
![alt text](https://raw.githubusercontent.com/dcooray42/RTv1/master/photo/RTv1_1.jpeg)
![alt text](https://raw.githubusercontent.com/dcooray42/RTv1/master/photo/RTv1_2.jpeg)
![alt text](https://raw.githubusercontent.com/dcooray42/RTv1/master/photo/RTv1_3.jpeg)
![alt text](https://raw.githubusercontent.com/dcooray42/RTv1/master/photo/RTv1_4.jpeg)

## Compiler avec
* Minilibx - Librairie graphique

## Licence
* Minilibx - License BSD: Copyright Olivier Crouzet - 2014

## Note
125/100

## Auteur

* **Dimitri Cooray** - [Lien vers github](https://github.com/dcooray42)
