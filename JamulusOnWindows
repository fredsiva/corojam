# Installation de Jamulus sous Windows 10

## Installation de Jamulus
* Télécharger le fichier Jamulus pour Windows le plus récent (au 03/04/2020 Jamulus-3.4.5-installer.exe)
* Lancer l’exécution du fichier Jamulus-3.4.5-installer.exe
* Effectuer l’installation en dépit des messages de sécurité relatifs aux fichiers téléchargés de l’internet

## Installation de ASIO4ALL
* Se rendre sur le site ASIO http://www.asio4all.org 
* Télécharger la version la plus récente de ASIO4ALL (au 03/04/2020 version 2.14)
* Lancer l’exécution du fichier ASIO4ALL_2_14_English.exe
* Effectuer l’installation en dépit des messages de sécurité relatifs aux fichiers téléchargés de l’internet

## Configuration de Jamulus
* Lancer l’application Jamulus

La fenêtre suivante apparaît :
![jamulus](JamulusMainWindow.png)

* Dans le bas de l’écran principal de Jamulus, cliquer sur le bouton Settings.

La fenêtre suivante apparaît :

![jamulus](JamulusSettings.png)

Dans le coin supérieur gauche, le champ ‘Device’ doit contenir ‘ASIO4ALL v2’

## Configuration du son sous Windows
* Dans les paramètres de Windows, sélectionner l’option ’Son’.

La fenêtre suivante apparaît :

![jamulus](WindowsSound.png)

* Vérifier l’activation du périphérique de sortie (par exemple Casque ou Haut-parleurs (Realtek High Definition …). Attention, le choix des haut-parleurs n’est permis que si ceux-ci sont rendus inactifs lors du raccordement du casque).

* Vérifier l’activation du périphérique d’entrée. Augmenter suffisamment le volume du microphone.

## Configuration ASIO
* Dans le coin inférieur gauche de l’écran Settings, cliquer sur le bouton ASIO Setup.

La fenêtre suivante apparaît, lorsque la clef plate située en bas à droite et le petit signe ’+’ situé en haut à gauche ont été cliqués. 

Cette image est l’exemple d’une implémentation **particulière** sous Windows 10. En effet, le nombre et la nature des périphériques d’entrée et de sortie peuvent varier d’une marque d’ordinateur à l’autre (présence d’une entrée line-in séparée, connexion combinant casque et micro, …). A cette liste de périphériques, peuvent s’ajouter ceux correspondant à des dispositifs tels que microphone USB, carte son, …

![jamulus](ASIO4ALL.png) 

Dans la partie gauche de l’écran, sous ‘WDM Device List’, 
* Sélectionner un dispositif de sortie, en l’occurence celui correspondant à la prise casque de l’ordinateur
* Sélectionner un dispositif d’entrée, par exemple le microphone de l’ordinateur

* Dans la partie droite de l’écran, cocher la case ‘Always Resample 44.1kHz <-> 48kHz’. Si ceci n’est pas fait, Jamulus peut se bloquer, indiquant qu’il doit fonctionner avec une fréquence d’échantillonnage de 48000Hz.

**Attention ! Il ne faut sélectionner qu’un seul périphérique d’entrée et un seul périphérique de sortie et il faut sélectionner les bons ! En effet, la sélection d’un périphérique peut inhiber le fonctionnement d’un autre !!!**


## Sauvegarde de la configuration
* Fermer toutes les fenêtres et terminer l’exécution de Jamulus
* Relancer Jamulus
* Cliquer sur le bouton Connect
* Indiquer l’adresse du serveur Jamulus Corojam 217.15.232.29

