#Exercice 3

**1.**
* mkdir exo
* cd exo
* /home/users/100/bmullers/exo
* cd
* cd exo
* cd ..

**2.**
* cat > es1.txt
* CTRL + D
* mkdir essai2

**3.**
* cp es1.txt essai2
* cd essai2
* mv es1.txt es1-copie.txt

Il est possible de le faire en une seule opération, en faisant:
* cp es1.txt /essai2/es1-copie.txt

**4.**
La commande ls * affiche tous les fichiers du dossier et de ses sous dossiers
Pour voir seulement les fichiers commençant par "es" on utilisera la commande:
* ls es*

**5.**
Pour supprimer un fichier avec demande de confirmation, on utilisera la commande:
* rm -i nom du fichier
Pour supprimer un répertoire et ses sous-répertoires on utilisera la commande:
* rm -r nom du répertoire

**6.**
* sed '51!d' nom du fichier

**7.**
Grep affiche les lignes des fichiers texte contenus dans /etc/ et ses sous-répertoires contenant le mot "passwd" et affiche un message d'erreur à chaque fois qu'on essaie de lire un répertoire ou qu'un permission nous est déniée
Pour ne pas afficher de messages d'erreur on peut ajouter l'option -s:
* grep -s passwd /etc/*

**8.**
* find -iname a*

**9.**
* find -newer nom du fichier spécifié

**10.**
* find -name *.o -delete


