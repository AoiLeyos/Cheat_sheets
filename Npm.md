1.
- npm config set <key> <value> : pour changer les valeurs par défaut des données.
- npm config get init-module : pour ajouter des questions de setup, pour ajouter des parametres.
- npm init : pour la création d'un package.json .
- npm init tag (ex: --yes) pour répondre au question automatiquement avec les données présentes.

les éléments du package.JSON: 
Name :Obligatoire ,limité a 214 character, il ne doit pas inclure de majuscule ne dois pas inclure js ou node également et ne dois pas contenir de caractère invalide pour une URL.

Version: Obligatoire, sont attribut est numérique souvent sous le format x.y.z,  x>y>z.

description : facultatif, mais dois contenir la description du projet, si on publie le package sur npm, car cela aide pour a recherche .

main : c'est le point d'entré du module, s'il n'est pas définis il chercheras 'index.js'

author : Ce champ contien l'auteur du package, on l'écris souvent "Name {email} {url}".

licence : il permet de définir le niveau d'open source accordé au module nous pouvons nous reporté a https://choosealicense.com pour savoir la license nécessaire a notre projet.

private : pas souvent utilisé mais si il est "set" sur "true" il empeche la publication du package sur npm.

scripts : elle a pour valeur un objet contenant un ensemble de commandes. ces commandes seront executées soit par le projet, soit manuellement, pour effectuer des actions comme: 
start,pour démarrer le projet localemet.
test,pour lancer les tests définis.
build, pour compiler le projet pour le préparer au déploiement.

bugs : une ligne qui contien l'url vers la quelle rediriger lors d'un bug l'utilisateur

dependencies : 
elle contient les dependances externes donc le projet a besoin pour fonctionner, npm installera ces dépendances en même temps que le module dans lequel se trouve le fichier de configuration courant, il sera parcour lors de l'utilisation de la commande "npm install"

devDependancies : 
pour définir toutes les dependance utilisés uniquement lors du développement , elle ne seront pas installer en cas d'utilisation du module et ne sont utile que pour l'étape de développement.