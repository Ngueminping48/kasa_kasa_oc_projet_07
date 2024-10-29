# kasa_kasa_oc_projet_07

Kasa 🏠🏢
         
Site live - README en Français - English README
Description FR :
Ceci est un projet réalisé dans le cadre du programme de formation Développeur Front-end JavaScript React chez OpenClassrooms
Implémentez le front end d'une application de location de logements. Mettez en place des composants avec React et les routes de l'application avec React Router.
Compétences évaluées :
•	Créer des composants avec React ⚛️
•	Développer les routes d'une application web avec React Router 🛣️
•	Initialiser une application web avec un framework 🚀
Situation (fictive) du projet :
Développeur freelance, missionné en tant que Développeur Front-end, une entreprise spécialisée dans la location d’appartements entre particuliers depuis près de 10 ans. .
L’entreprise souhaite faire une refonte totale de leur site pour passer à une stack complète en JavaScript avec NodeJS côté Back-end et React côté Front-end.
Mon rôle a été de développer le front-end de l’application, en utilisant les composants React, les routes React Router et en respectant les maquettes Figma.
Contraintes techniques :
•	Outils :
o	Create React App.
o	React Router.
o	L’utilisation de Sass est optionnelle. CSS est à utiliser par défaut.
o	Pas de librairie React externe.
•	React :
o	Structure logique des différents fichiers.
o	Découpage en composants modulaires et réutilisables (Un composant par fichier).
o	Il est recommandé d’utiliser des composants fonctionnels au lieu des composants classes.
o	Utilisation des props entre les composants.
o	Utilisation du state dans les composants quand c'est nécessaire.
o	Gestion des événements.
o	Utiliser les listes autant que possible en itérant dessus (par exemple avec map).
•	React Router :
o	La logique du routeur est réunie dans un seul fichier.
o	Il existe une page par route.
o	Les paramètres des routes sont gérés par React Router dans l'URL pour récupérer les informations de chaque logement.
o	La page 404 est renvoyée pour chaque route inexistante, ou si une valeur présente dans l’URL ne fait pas partie des données renseignées.
o	Général : Le code ne doit pas produire d'erreur ou de warning dans la console.
Contraintes fonctionnelles :
•	Pour le défilement des photos dans la galerie (composant Gallery) :
o	Si l'utilisateur se trouve à la première image et qu'il clique sur "précédent", la galerie affiche la dernière image.
o	Inversement, quand l'image affichée est la dernière de la galerie, si l'utilisateur clique sur "suivant", la galerie affiche la première image.
o	S'il n'y a qu'une seule image, les boutons "suivant" et "précédent" n'apparaissent pas.
o	La galerie doit toujours rester de la même hauteur, celle indiquée sur la maquette Figma. Les images seront donc coupées et centrées dans le cadre de l’image.
•	Collapse :
o	Par défaut, les Collapse sont fermés à l'initialisation de la page.
o	Si le Collapse est ouvert, le clic de l'utilisateur permet de le fermer.
o	Inversement, si le Collapse est fermé, un clic permet de l'ouvrir.
Installation :

2.	Installer toutes les dépendances pour le front-end:
•	npm install ou yarn
3.	Lancer le front-end:
•	npm start ou yarn start
Le front-end sera lancé à l'URL: http://localhost:3000/Kasa/.
Développé avec :
•	Visual Studio Code - Éditeur de texte
•	Sass - Préprocesseur CSS
•	React 18 - Bibliothèque JavaScript libre développée par Facebook
•	Create React App - Boîte à outils créée par Facebook, qui est la référence pour initier un projet React
•	React Router V6 - Bibliothèque de routage pour React
•	GitHub - Outil de gestion de versions
•	GitHub Pages - Outil d’hébergement
