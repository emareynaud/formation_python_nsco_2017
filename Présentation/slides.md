------------------

# Python

![python](http://i.imgur.com/bc2xk.png)


------------------


# Programme des 5 jours:


  * Lundi 24 avril 2017 (matin et après-midi):
    * Installation (distribution Anaconda + packages)
    * Bases de la programmation Python

  * Mardi 25 avril 2017 (matin et après-midi)
    *  Calcul scientifique : modules NumPy, SciPy
    * Visualisation : module Matplotlib

  * Mercredi 26 avril 2017 (matin)
    *  Manipulation de fichiers: os, glob, re
    *Cas pratiques

  * Jeudi 27 avril 2017 (matin):
    * Pandas (manipulation de dataframe + Titanic dataset)
    * Seaborn (visualisation de données statistiques)

  * Vendredi 28 avril 2017 (matin):
   * Interfaçage Python/R software et équivalence dans StatsModels


 



------------------

# Pour anticiper les réclamantions

  * ça va aller un peu trop vite
  * les supports de court sont légers.
  * tout ne va pas vous être utile.

# En revanche:

  * il existe de très bons supports de cours
  * les formateurs sont des beaux gosses


------------------

# Historique

  * Créé en 1989 par Guido Van Rossum.
  * Version 1.5 en 1999
  * Aujourd'hui 3.6
  * Debut du python scientifique en 2005 par Travis Oliphant avec numpy
  * Aujourd'hui 6e language
  * Aujourd'hui 1er language pour l'analyse de données.

------------------

# Pourquoi python:
  * language ancien donc mûr
  * language généraliste
  * language orienté object
  * philosophie = simplicité de relecture du code.
  * le même language pour web, admin, analyse data, ...
  * libre
  * grande commmunauté
  * facile à enseigner
  * très complet
  * communauté qui fait don de ses codes.


------------------

# Utilisateurs de python

  * Google
  * Nasa
  * Instagram
  * Nous


------------------

# Idée en vrac

  * un language **interprété**
  * Pas d'environement de développement, éditeur, debuggeur (il faut en trouver un, spyder pour nous)
  * Peu de librairies officielles
  * les modules scientifiques sont developpés indépendemment
  * Il existe plusieurs interpréteurs (CPython, IronPython, PyPy, Jython)
  * On utilise le plus connu : CPython


------------------

# Installation

# C'est pas si facile car:

  * Il y a plusieurs versions 2.7 et 3.5, 3.6, on ne sait pas laquelle choisir.
  * Sous OSX et linux c'est déjà installé mais c'est souvent pas la bonne version
  * Il faut aussi installer toutes les librairies dont on a besoin
  * Les libairies scientifiques sont en C/C++/Fortran il faut un compilateurs!!
  * Python fournit un installateur de paquet officiel pip (site pypi) mais ça marche pas quand c'est compilé.
  * parfois c'est sur github
  * arbre de dépendance complexe.



------------------

# Sous OSX

  * il y a déjà python mais pas les numpy, scipy, Qt
  * homebrew
  * macport
  * conda


------------------ 

# Sous windows

  * python.org + http://www.lfd.uci.edu/~gohlke/pythonlibs/
  * winpython (choix à Gerland)
  * conda


------------------

# sous linux (ubuntu, debian)

  * c'est déjà installé
  * python (=python2) et python3 (=python3.4)
  * certains paquets avec:
    ```
      sudo apt-get install python-numpy
      sudo apt-get install python3-numpy
    ```
  * d'autres avec :
    ```
      pip install numpy
      pip3 install numpy
    ```
  * conda

------------------

# Environement virtuel

  * permet pour chaque projet de choisir une version de python + chaque librairie
  * conda intègre les environnements virtuels


------------------

# Installation de conda.

  * Installer le paquet seaborn
```
  conda install seaborn
```



------------------

# URL à lire tout seul

  * www.opentechschool.org
  * http://www.scipy-lectures.org/
  * http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/
  * http://feldboris.alwaysdata.net/blog/pages/presentations/AtelierPythonUTBM/#slide45



