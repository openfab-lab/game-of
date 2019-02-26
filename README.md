# Game of
>le dev d'un jeu basé sur les expériences de terrain d'Openfab, un développement collaboratif non linéraire basé sur le soft Twine et l'usage de github comme tool de partage.


[Jorgininho](https://github.com/Jorgininho) et [moi](https://github.com/nicolasdb) avons joué à [crée ton fablab](https://meditmoiunfablab.wordpress.com/2013/03/10/cree-ton-fablab-le-jeu-a-imprimer/), un jeu développé dans un fablab de Vendée 🇫🇷 (en 2013, malheureusement fermé maintenant).  
Belle initiative mais peu convainquante. C'est pas le jeu auquel on va jouer plusieurs fois et les mécaniques de jeu ne sont pas réalistes.   
On ne tire pas au sort les machines et matériaux nécessaire à un projet donné.  
On ne les perd pas non plus à la fin.  
L'unité de temps est la semaine.... lol   
![image](https://user-images.githubusercontent.com/12049360/53304256-46b25e80-3873-11e9-9139-e3759bab715b.png)

## les objectifs du jeu

L'intérêt d'un jeu fablab est double,  
1. pour le noob, faciliter l'introduction aux règles en usage dans le fablab
2. pour l'équipe, le jeu comme simulateur du modèle interne.
Permet de prendre un recul sur les interactions dans le fablab, pour simuler et tester des choix grâce à des cycles de jeux plus rapides pour une itération accélérée.

C'est un excercie d'empathie aussi, comme un jeu de rôle, on joue des personnages, tour à tout client, membre, partenaire. On se projette dans les projets sans les faire.  
Auxquels on ajoute l'expérience de 7 ans de gestion de fablab pour l'aléatoire, les fail, les win, les scénarios concrets et les lolcat.

**Nos remarques et idées pour une évolution du jeu.**
- conditions de victoire? vision du fablab.
- des paramètres aléatoires ou fixe.
   - les skills,
   - les machines,
   - les matériaux,
- des personnages dont on tire au hasard les skills en début de partie (comme les 7 premières lettres au scrabble)
- en plus de cartes "hasard", ajouter une intensité ou une probabilité via un lancé de dé.
- un niveau de réputation est représenté par le nombre de lancé de dé.
Une bonne réputation peut influencer la chance, la probabilité de faire "1" est plus basse avec un 4D6 qu'avec 1D6, mais ne nous protège pas non plus de l'Epic Fail.
- une unité de monnaie? Quelle type de valeur utilisons nous? quel référenciel?
- Evolution de son personnage. LevelUp, profil.
- des cartes qui tuent. Les tuiles massivent qui te ruine le slip si t'est pas suffisament à l'équilibre. (Comme dans **Exploding kitten**.)  
- Mais peut-être qu'il y aurait aussi de quoi eviter le pire. Idunno. (Comme dans **Exploding kitten**.)  
- et une unité de temps contraignante et un timer, parce que la vie est dure et le lapin blanc est toujours en retard.    
**As a fabmanager, if you have time, you ain't doing it right.**

> hum...  actually, from a non-linear, non-subjective viewpoint, time is more like a big ball of wibbly wobbly timey wimey stuff

## Pourquoi non-linéraire?
Je ne sais pas, et pourquoi pas? J'ai envie de tester.  
Comme tout jeux, s'il n'y a pas de place à la créativité et aux choix multiples, l'histoire peut vite perdre de son intérêt.  
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
