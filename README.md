# Game of
>le dev d'un jeu basé sur les expériences de terrain d'Openfab, un développement collaboratif non linéraire basé sur le soft Twine et l'usage de github comme tool de partage.


[Jorgininho](https://github.com/Jorgininho) et [moi](https://github.com/nicolasdb) avons joué à [crée ton fablab](https://meditmoiunfablab.wordpress.com/2013/03/10/cree-ton-fablab-le-jeu-a-imprimer/), un jeu développé dans un fablab de Vendée 🇫🇷 (en 2013, malheureusement fermé maintenant).  
Belle initiative mais peu convainquante. C'est pas le jeu auquel on va jouer plusieurs fois et les mécaniques de jeu ne sont pas réalistes.   
On ne tire pas au sort les machines et matériaux nécessaire à un projet donné.  
On ne les perd pas non plus à la fin.  
L'unité de temps est la semaine.... lol   
![image](https://user-images.githubusercontent.com/12049360/53304256-46b25e80-3873-11e9-9139-e3759bab715b.png)

## les objectifs du jeu




## Pourquoi non-linéraire?
Je ne sais pas, et pourquoi pas?  
Comme tout jeu, s'il n'y a pas de place à la créativité et aux choix multiples, l'histoire peut vite perdre de son intérêt.  
Et il est difficile de scénariser linérairement les choix multiples.   

_petit tuto pour débuter._ http://www.adamhammond.com/twineguide/

```
Twine is an open-source tool for telling interactive, nonlinear stories.

You don't need to write any code to create a simple story with Twine, but you can extend your stories with variables, conditional logic, images, CSS, and JavaScript when you're ready.

Twine publishes directly to HTML, so you can post your work nearly anywhere. Anything you create with it is completely free to use any way you like, including for commercial purposes.

Twine was originally created by Chris Klimas in 2009 and is now maintained by a whole bunch of people at several different repositories.

```
[_Twine_](https://twinery.org/)
J'ai installé la toute dernière version instable, la V2.3.0 beta 2.  
_Ouais, parce que j'aime vivre dangereusement._

Un des problèmes mentionnés dans leur wiki est qu'il n'est pas possible de [collaborer sur une histoire](http://twinery.org/wiki/twine2:collaborate_with_someone_else) (not right now) sans passer par un échange d'archive qui peut être un peu bordélique à cause de multiple version.  

MAIS!   
En installant leur application, on évite de passer par le cache du navigateur web.
L'installation ne permet pas de choisir où est sauvé le fichier d'histoire mais on le trouve facilement sur windows dans les documents de l'utilisateur.
>C:\Users\xxxxx\Documents\Twine\Stories

Les fichiers "histoire" sont de simples fichier .html et donc en tant que tel, sont évidemment très bien géré par Github.  
En créant un dépôt du même nom "Stories" placé au même endroit dans  
> \Documents\Twine\..

Toutes les "histoires" seront ainsi partagées via le dépôt avec toute la puissance des versions de GIT.

```
! forcer le renommage du repo en /Stories dans le dossier cible /Twine
pour que les fichiers soient reconnu par le soft twine.
```
