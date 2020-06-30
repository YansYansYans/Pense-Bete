# Pense-Bête #

## Installation SASS ##

Se rendre sur ce lien https://github.com/sass/dart-sass/releases/tag/1.26.9 et installer le package selon votre ordi

L'extraire et le placer dans le dossier de votre site web

Dans le dossier du site web, créer la route suivante : assets/scss/styles.scss

Dans le dossier du site web, créer le dossier : css

Dans le cmd du dossier du site, entrer : dart-sass\sass

Puis entrer : dart-sass\sass assets/scss:css

Sass a été créé avec succés mais pour qu'il s'exécute automatiquement, entrer : dart-sass\sass assets/scss:css --watch


## Commande MySQL ##

### Implémenter MySQL ###
 
Pour exécuter MySQL dans le dossier du site, entrer : set PATH=%PATH%;C:\"Program Files"\MySQL\"MySQL Server 5.6"\bin

Puis entrer : mysql

Pour créer un compte, entrer : mysql -h localhost -u root -pmdp (remplacer le mpd par votre mdp)

Pour vous connecter, entrer : mysql -u root -p

Puis rentrer votre mot de passe si le message suivant apparait : Enter password:

### Naviguer dans MySQL ###

Créer une base de donnée : CREATE DATABASE nom_base;

Supprimer une base de donnée : DROP DATABASE nom_base;

Afficher les bases de données : SHOW datababes;

Utiliser une base de donnée : USE nom_base;

Afficher les tables d'une base de donnée : SHOW tables;

Afficher le contenu d'une table : DESCRIBLES nom_table;