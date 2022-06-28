# Pushswap

Le Pushswap est un projet de milieu d'année. Le jeu Pushswap est constitué de deux listes chaînées, l'une sera nommé l_a et l'autre l_b. 
Au départ, la liste l_b est vide et la liste l_a contiendra un certain nombre de nombres uniques positifs ou négatifs. 
Le but du jeu est de faire en sorte que la liste l_a contienne les mêmes nombres, mais dans l'ordre croissant. 

Pour ce faire, nous n'avons que les opérations suivantes :

• sa : permute les 2 premiers éléments de l_a (ne fait rien si pas assez d'éléments)

• pa : prend le premier élément de l_b et le met en première position dans l_a (si l_b est vide, ne fait rien)

• pb : prend le premier élément de l_a et le met en première position dans l_b (si l_a est vide, ne fait rien)
 est composé de deux listes de nombres nommées l_a et l_b, Au début, l_b sera vide et l_a contiendra un certain nombre de nombres positifs ou négatifs, l'objectif du jeu est de trier l_a


## But du programme

Ce projet a lui aussi pour but de nous apprendre l’optimisation. En effet, grâce à des listes chainées et certaines opérations, le principe était de remettre une liste de chiffre dans l’ordre.

## Fonctions autorisées

```

	• Write 
	• Malloc
	• free
	
```

## Mise en route

Ces instructions vous permettront d'obtenir une copie du projet opérationnel sur votre machine locale à des fins de développement et de test.

### Pré-requis

De quoi avez-vous besoin pour installer le logiciel et comment l'installer ?

```

gcc
make

```

### Installation

Compilation du projet

```
make
```

Lancement du projet

```
./push_swap [l_a]

exemple :

./push_swap 2 1 3 6 5 8

sa pb pb pb sa pa pa pa
```






