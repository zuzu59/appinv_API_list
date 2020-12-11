# appinv_API_list
Petite application Android de démo de lecture d'une API en AppInventor (Scratch)

zf201211.1650

<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:1 title:1 charForUnorderedList:* -->
## Table of Contents
* [Buts](#buts)
* [Problématiques](#problématiques)
* [Moyens](#moyens)
  * [Langage de programmation](#langage-de-programmation)
  * [Environnement de développement](#environnement-de-développement)
  * [Partage d'écran du smartphone](#partage-décran-du-smartphone)
  * [Source de données, kata-API](#source-de-données-kata-api)
* [Installation](#installation)
  * [Sur son ordinateur pour le développement](#sur-son-ordinateur-pour-le-développement)
    * [Interface de développement](#interface-de-développement)
    * [Application pour les tests en temps réel sur son smartphone](#application-pour-les-tests-en-temps-réel-sur-son-smartphone)
    * [Partager l'écran de son smartphone dans une fenêtre du browser (vidéo conférence)](#partager-lécran-de-son-smartphone-dans-une-fenêtre-du-browser-vidéo-conférence)
  * [Application autonome sur son smartphone Android](#application-autonome-sur-son-smartphone-android)
* [Utilisation](#utilisation)
* [Comment partager son code après ?](#comment-partager-son-code-après-)
  * [Exporter le code App Inventor 2](#exporter-le-code-app-inventor-2)
  * [Partage visuel du code Scratch](#partage-visuel-du-code-scratch)
  * [Partage visuel de l'interface (designer) de l'application du smartphone](#partage-visuel-de-linterface-designer-de-lapplication-du-smartphone)
  * [Partage de l'application compilée .apk](#partage-de-lapplication-compilée-apk)
<!-- /TOC -->


## Buts
Faire une petite application Android qui va rechercher des info dans une API JSON pour les afficher sur le smartphone.


## Problématiques
Ce n'est pas facile d'écrire une application simple pour Android, cela demande toute une installation d'un IDE *lourd* mais surtout d'une *compréhension* de l'usine à gaz pour arriver à fabriquer un fichier *.apk* pour l'installation sur le smartphone.<br>
 Mais aussi pour pouvoir la tester rapidement et pas devoir en permanence télécharger l'application et l'installer sur le smartphone.


## Moyens
### Langage de programmation
On va utiliser pour cette petite démo un langage informatique très rigolo, le *Scratch*.
https://fr.wikipedia.org/wiki/Scratch_(langage)

![Image](https://raw.githubusercontent.com/zuzu59/appinv_API_list/main/img/code_scratch_hello_world.png)

Qui va nous permettre de mieux comprendre l'utilisation des blocs *logiques* en informatique.


### Environnement de développement
Et pour faire une application pour un smartphone Android, on va utiliser l'excellent site *Scratch* du MIT
http://appinventor.mit.edu/explore/get-started

![Image](https://raw.githubusercontent.com/zuzu59/appinv_API_list/main/img/screen_designer.png)

*AppInventor* est vraiment un sacré IDE tout en ligne qui permet de d'écrire, de tester et de *builder* un fichier *.apk* pour un smartphone Android.
Il de dessiner l'interface graphique et d'écrie le code de l'application, puis de pouvoir le tester, en temps réel sur son smartphone, sans devoir le compiler et télécharger en permanence.


### Partage d'écran du smartphone
On va aussi utiliser l'application *AirDroid* sur son smartphone, qui va permettre de *partager* l'écran de son smartphone dans une *fenêtre* de son browser afin de pouvoir le *voir* quand on se trouve en *vidéo conférence* Zoom par exemple.

![Image](https://raw.githubusercontent.com/zuzu59/appinv_API_list/main/img/airdroid.png)


### Source de données, kata-API
Pour l'instant notre source de données se trouve provisoirement sur:

http://86.119.30.245:1337/beers.php



## Installation
### Sur son ordinateur pour le développement
#### Interface de développement
Simplement charger cette URL dans votre browser favoris:

http://ai2.appinventor.mit.edu/

Bien entendu, il faut s'authentifier avec son compte Google !

Puis après, dans le menu *Projects* il faut *importer un projet .aia* depuis son ordinateur:

https://github.com/zuzu59/appinv_API_list/blob/main/API_list.aia


#### Application pour les tests en temps réel sur son smartphone
Et enfin, sur son smartphone, il faut encore installer le *MIT AI2 Companion App*, afin de pouvoir *connecter*, via le WIFI, très facilement son smartphone à l'IDE pour pouvoir tester son application en temps réel sur son smartphone:

http://appinventor.mit.edu/explore/ai2/setup-device-wifi


#### Partager l'écran de son smartphone dans une fenêtre du browser (vidéo conférence)
Afin de pouvoir *partager* l'écran de notre smartphone, où tourne notre application, quand on se trouve en *vidéo conférence* Zoom par exemple. On doir encore installer l'application *AirDroid* sur son smartphone:

https://play.google.com/store/apps/details?id=com.sand.airdroid&hl=fr_CH&gl=US


### Application autonome sur son smartphone Android
Simplement charger, via le browser de son smartphone, le fichier *.apk* qui se trouve ici:

https://github.com/zuzu59/appinv_API_list/releases


## Utilisation
Pour l'instant quand on appuie sur le premier bouton, cela va chercher tous les noms des bières du *kata-API* pour les afficher dans sur l'écran.


## Comment partager son code après ?
*Scratch* est un code *graphique*, on ne peut donc pas le partager comme d'habitude sur Github. Il faudra être ici un peu plus imaginatif.


### Exporter le code App Inventor 2
Il faut pour cela aller dans le menu *Project* puis de faire *Export select project (.aia) to computer*. C'est ce fichier que l'on va pouvoir partager via Github. Cela permettra à d'autre de pouvoir faire un *import* de ce fichier pour pouvoir le modifier dans *App Inventor 2*.


### Partage visuel du code Scratch
C'est quand même aussi pratique de pouvoir *voir* le code *Scratch* sans devoir importer le fichier *.aia*. Pour cela, quand on se trouve dans la fenêtre du code *blocks*, on peut choisir avec le bouton de droite de la souris *Download Blocks as image*. Ce fichier on pourra alors aussi le partager sur Github.


### Partage visuel de l'interface (designer) de l'application du smartphone
C'est aussi pratique de pouvoir montrer comment on a *disposé* les éléments sur l'écran du smartphone. Pour cela, il faut simplement en faire une *copie d'écran* avec sons outil favoris de copie d'écran. A nouveau, on peut le partager sur Github


### Partage de l'application compilée .apk
Finalement c'est une bonne chose de *partager* son application compilée sans devoir l'*importer* et la *compiler* dans *App Inventor 2*. Pour cela, il faut en premier *compiler* (menu build) un fichier *.apk*. Puis après on peut le *partager* via la fonctionnalité *releases* de Github. 





.
