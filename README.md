
Application Kotlin/XML avec internationalisation
Description

Ce projet est une application simple qui montre comment internationaliser une application Kotlin/XML. L'application a un bouton avec un texte en français qui peut être traduit en anglais.

Prérequis

Android Studio
Kotlin plugin pour Android Studio
Installation

Clonez ce projet dans votre répertoire local.
Ouvrez le projet dans Android Studio.
Assurez-vous que le plugin Kotlin est installé et activé.
Exécution

Cliquez sur le bouton "Run" dans Android Studio.
L'application s'exécutera sur votre appareil ou sur un émulateur.
Internationalisation

L'application utilise les fichiers de ressources XML pour internationaliser le texte du bouton. Les fichiers de ressources XML sont stockés dans le dossier res/values.

Le fichier strings.xml contient le texte du bouton en français.
Le fichier strings_en.xml contient le texte du bouton en anglais.
Pour changer la langue de l'application, vous pouvez modifier la configuration de la langue de votre appareil.

Fichiers

app/build.gradle : Fichier de configuration Gradle pour l'application.
app/src/main/java/com/example/internationalization/MainActivity.kt : Fichier source Kotlin pour l'activité principale.
app/src/main/res/layout/activity_main.xml : Fichier de mise en page XML pour l'activité principale.
app/src/main/res/values/strings.xml : Fichier de ressources XML contenant le texte du bouton en français.
app/src/main/res/values/strings_en.xml : Fichier de ressources XML contenant le texte du bouton en anglais.
