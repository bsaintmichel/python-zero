# Python Scientifique de Zéro

[Brice Saint-Michel](bsaintmichel@gmail.com), Université Gustave Eiffel

Ici, nous allons dresser un aperçu rapide de ce que Python peut vous apporter si vous êtes physicien.ne ou physico-chimiste. Aucune connaissance n'est requise a priori : on part de zéro, même si, bien entendu, vous irez plus vite si vous connaissez déjà des langages de programmation (notamment : MATLAB). L'apprentissage s'effectue directement en manipulant vous-mêmes du code Python interactif, afin de mettre un minimum de distance entre la théorie et la mise en pratique.

Cliquez sur l'icône ci-dessous pour accéder aux tutoriels !

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bsaintmichel/PythonZero/HEAD)

--------------------------
## Sommaire 

Les tutoriels sont divisés en des _tutoriels_ (de 1 à 4) que je conseille d'étudier dans l'ordre, puis ensuite d' __applications__ (de A à ..) qui sont assez largement indépendants les uns des autres et qui peuvent être effectués dans le désordre.

### Tutoriels : la base 

1. [Premiers pas, variables, booléens](./Tutorial_1_SimpleThings.ipynb) va partir de zéro et vous offrir la possibilité de :
* créer des variables simples (entiers, flottants, chaînes de caractères)
* effectuer des opérations de base (additions, multiplications) 
* afficher vos résultats de manière simple
* convertir ces variables dans un autre format quand cela est nécessaire. 
* comparer des résultats et effectuer des opérations sur les variables _booléennes_

2. [Listes, Tuples, Dictionnaires](./Tutorial_2_ListsTuplesDicts.ipynb) vous fera découvrir les conteneurs en Python : 
* on verra comment créer et indicer, faire des tranches de listes, tuples, dictionnaires et comprendre 
* on s'intéressera ensuite à la manipulation efficace de ces objets en utilisant leurs _méthodes_ associées.
* on examinera enfin la notion de _mutabilité_ d'objets en Python.

3. [Boucles, conditions, ](./Tutorial_3_Loops.ipynb) vous libérera des tâches répétitives en les incluant dans une, ou plusieurs boucles !
* on commencera par la boucle `for`, qui introduira également l'usage des objets `range` et `enumerate`
* on verra ensuite le bloc d'instructions `if ... else`
* on se penchera sur le cas des boucles `while`
* et on verra rapidement le rôle de l'instruction `break`

4. [Bibliothèques, imports, aide](./Tutorial_4_Imports.ipynb) va vous indiquer comment ne pas réinventer la roue en utilisant des bibliothèques de fonctions que d'autres ont déjà développées.
* on commencera par la syntaxe pour appeler des modules déjà existants et utiliser leurs fonctions
* on continuera ensuite en définissant nos propres fonctions 
* et on terminera rapidement en créant notre propre module 

### Applications 

1. [NumPy](./Application_A_Numpy_Scipy.ipynb) va vous dévoiler la puissance des modules `NumPy` et `SciPy` pour vos applications scientifiques.