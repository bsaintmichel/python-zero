# Python Scientifique de Zéro

__Brice Saint-Michel__ (bsaintmichel on gmail), Université Gustave Eiffel

Ici, nous allons dresser un aperçu rapide de ce que Python peut vous apporter si vous êtes physicien.ne ou physico-chimiste. Aucune connaissance n'est requise a priori : on part de zéro, même si, bien entendu, vous irez plus vite si vous connaissez déjà des langages de programmation (notamment : MATLAB). L'apprentissage s'effectue directement en manipulant vous-mêmes du code Python interactif, afin de mettre un minimum de distance entre la théorie et la mise en pratique.

---------------------------------------

### À propos de l'environnement de travail

Si vous voulez en savoir plus sur Binder et Jupyter Notebooks, l'environnement de développement avec lequel vous travaillez, jetez un oeil à la [FAQ](./FAQ.md).

----------------------------------

### Accéder aux tutoriels interactifs 

Cliquez sur l'icône ci-dessous pour accéder aux tutoriels, même sans avoir rien installé sur votre PC !

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/bsaintmichel/PythonZero/HEAD)

---------------------------------

## Sommaire 

Les tutoriels sont divisés en des __tutoriels__ (de 1 à 6) que je conseille d'étudier dans l'ordre, puis ensuite d' __applications__ (de A à ..) qui sont assez largement indépendants les uns des autres et qui peuvent être effectués dans le désordre.

### La base 

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
* on commencera par la boucle `for`, qui introduira également les objets `range` et `enumerate`
* on verra ensuite le bloc d'instructions conditionnel `if ... else`
* on se penchera sur le cas des boucles `while`
* et on verra rapidement le rôle de l'instruction `break`

4. [Bibliothèques, imports, aide](./Tutorial_4_Imports_functions.ipynb) va vous indiquer comment ne pas réinventer la roue en utilisant des bibliothèques de fonctions que d'autres ont déjà développées.
* on commencera par la syntaxe pour appeler des modules déjà existants et utiliser leurs fonctions
* on continuera ensuite en définissant nos propres fonctions 
* et on terminera rapidement en créant notre propre module 

5. [Fichiers et dossiers](./Tutorial_5_Files.ipynb) va vous montrer comment gérer et trouver des fichiers et des dossiers en Python. Dans l'ordre : 
* on verra comment ouvrir un fichier et le fermer, et comment lire et écrire à l'intérieur de ceux-ci. 
* on verra rapidement comment enregistrer des variables compliquées au format `JSON`
* on s'intéressera ensuite au module `os` qui permet de changer de répertoire de travail et d'en créer
* on verra enfin le module `glob` qui permet d'effectuer une recherche de fichiers et de dossiers.

6. [Quelques astuces supplémentaires](./Tutorial_6_Extras.ipynb) va vous simplifier la vie en Python et vous permettre de travailler depuis votre PC en _hors-ligne_ (ou presque):
* On cmmencera par les affectations multiples pour économiser des lignes de code.
* On apprendra à formater joliment les nombres quand on les convertit en chaînes de caractère.
* On découvrira les _listes en compréhension_ pour rendre son code plus élégant.
* On évoquera la fonction `zip()` qui permet de boucler sur plusieurs éléments. 
* On verra enfin comment __installer Python sur votre PC__ avec Anaconda ou Python & VSCode.

### Les applications 

A. [Numpy](./Application_A_Numpy.ipynb) va vous dévoiler la puissance du module Numpy pour vos applications numériques.
  * on commencera par introduire un nouveau type de données, les tableaux `np.ndarray`.
  * on verra ensuite les constantes et fonctions mathématiques présentes sur Numpy.
  * on évoquera quelques fonctions _inclassables_ et utiles pour les scientifiques .
  * on parlera des fonctions d'algèbre et de régression linéaire avec le sous-module `linalg` .
  * on continuera avec le sous-module `random` permettant de générer des nombres aléatoires.
  * on poursuivra avec le sous-module `fft` permettant de faire des _transformées de Fourier_ discrètes.

B. [Matplotlib](./Application_B_Matplotlib.ipynb) vous permettra de tracer vos graphes préférés, voire de les animer.
  * je commencerai avec quelques généralités sur la structure des figures en Matplotlib.
  * on verra ensuite, pour ceux qui sont pressés, comment tracer une figure _vite fait mal fait_.
  * on continuera avec les méthodes permettant de modifier et de personnaliser vos figures.
  * on s'intéressera ensuite à quelques tracés bien particuliers : images, aires entre courbes, histogrammes, nuages de points complexes, et surfaces 3d.
  * j'indiquerai comment exporter ses figures proprement au format `.png`, `.pdf`, mais également `.tex`.
  * on examinera enfin comment faire des tracés animés et interactifs.

C. [Scipy](./Application_C_Scipy.ipynb) commence là où s'arrête `Numpy`, et est très puissant pour le traitement de signal et la résolution numérique de problèmes
  * on parlera corrélations, convolutions, filtres et recherche de maxima locaux dans le sous-module `signal`.
  * on verra ensuite les fonctions qui interpolent un signal dans le sous-module `interpolate`.
  * on minimisera/maximisera une fonction, on trouvera ses zéros et on fittera des courbes avec `optimize`.
  * on étudiera ensuite comment résoudre une équation différentielle avec le sous-module `integrate`.
  * on traitera enfin quelques options sympathiques, comme par exemple _ouvrir un fichier .mat de MATLAB_, ou faire une intégration avec la méthode des trapèzes !

D. [Pandas](./Application_D_Pandas.ipynb) vous permettra d'apprivoiser les `DataFrame`, une nouvelle classe qui s'apparente aux tableaux Excel
  * on verra comment créer ces `DataFrame` _ex nihilo_ ou à partir de fichiers texte (`.csv` ou `.xlsx`).
  * on accèdera aux données des `DataFrame` via leurs lignes, colonnes ou selon des conditions.
  * on examinera enfin comment modifier ces `DataFrame` en ajoutant/supprimant une colonne/ligne
  * on jettera un oeil aux opérations de groupe, notamment aux méthodes `.groupby()` et `.agg()`
  * on regardera enfin comment fusionner deux `DataFrame`, que ce soit par un `.merge()`, un `.join()` et un `.concat()` 

E. [Scikit-Image](./Application_E_ScikitImage.ipynb) vous montrera comment manipuler, traiter et extraire le plus possible de données de vos images, via _trois exemples_:
  * le premier exemple consiste à détecter des bulles et va introduire le seuil d'Ōtsu, les méthodes d'étiquetage (`label()` et `regionprops_table()`) et la dilatation morphologique d'une image binaire.
  * le deuxième exemple va tenter de détecter des particules et va utiliser pour cela du contraste adaptatif ([CLAHE](https://en.wikipedia.org/wiki/Adaptive_histogram_equalization#CLAHE)), des cartes de distance et une routine de _watershed_ avant d'étiqueter l'image.
  * le troisième exemple traitera enfin de détection d'images en utilisant un filtre de Canny ainsi qu'une transformée de Hough circulaire.

F. [Trackpy et OpenPIV](./Application_F_PIV_Tracking.ipynb) vous dira enfin comment calculer des champs de vitesse à partir de séquences d'images et comment détecter puis suivre des particules individuelles dans les images.
  * on verra en premier comment détecter des particules sur une image (encore !) sous `trackpy` avec l'algorithme de Crocker et Grier.
  * on regardera ensuite le dépouillement d'images multiples avec `trackpy.batch` et le suivi de particules avec `trackpy.link()`.
  * on s'intéressera enfin aux calculs de champs de vitesse par PIV avec `openPIV`.
  * je terminerai avec un exemple plus compliqué combinant les deux approches ce qui permet de suivre des particules qui bougent collectivement sur des assez grandes distances.
