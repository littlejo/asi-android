# Arret sur images sur Android

Ceci est la reprise du code de Benoit Valot.

Les buts du projet sont :

* récupérer le code source sous git ;
* corriger les bugs qui se sont accumulés avec les modifications du site ;
* améliorer l'application


# Ancienne indication

Copyright Valot Benoit 2010
Ce programme est publié sous licence GPL v3.

## Compilation

L'application utilise le widget Actionbar développé par Johan Nilsson sous licence Apache V2.
Les sources peuvent être téléchargées à cette adresse:
https://github.com/johannilsson/android-actionbar/tree/mimic-native-api
Compilez les dans un projet séparé, en l'indiquant comme bibliothèque, puis ajouter cette nouvelle bibliothèque à ce projet.
(Eclipse, Projet->properties->android)

L'application utilise la bibliothèque Android Support Livrary (v12) fourni avec Android,
ajoutant des fonctionnalités de versions récentes d'Android au ancien système.
http://developer.android.com/tools/extras/support-library.html
Sous Eclipse, installer le depuis le 'Android SDK manager'-> Extras -> Android Support Library
Ajouter le au project Android Tools -> Add support library
