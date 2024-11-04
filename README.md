# Réseau Social en PHP

## Description du Projet
Legacy Code : Prise en main d’un code existant sur une nouvelle technologie à partir d’une documentation fournie pour développer une plateforme de microblogging type réseau social. Ce projet a pour but de construire un réseau social en PHP, dans lequel les utilisateurs peuvent afficher et consulter les messages des autres membres sur différentes pages, en suivant un modèle de structure de code réutilisable.

## Compétences Développées
- Reprendre et modifier un code existant pour atteindre des objectifs spécifiques de développement
- Configurer et utiliser un serveur local (MAMP, WAMP, ou XAMPP)
- Expliquer le fonctionnement des échanges entre client et serveur
- Générer du code HTML à partir de PHP
- Manipuler le paramètre GET en PHP
- Créer des formulaires HTML avec PHP (niveau 2)
- Développer des fonctionnalités d'inscription et d'authentification (niveau 2)

## Stack Technique
- **Back-end** : PHP (utilisé avec un serveur local MAMP, WAMP ou XAMPP et une base de données MySQL ou MariaDB)
- **Front-end** : HTML / CSS

## Structure et Installation
### Configuration du Serveur
1. Installer et configurer MAMP, WAMP ou XAMPP.

### Importation de la Base de Données
1. Récupérer le fichier `Niveau1.sql` et l'importer dans phpMyAdmin.
2. Vérifier que la base de données `socialnetwork` est bien ajoutée.

### Installation des Fichiers PHP
1. Placer les fichiers PHP dans le répertoire `htdocs` sous un sous-répertoire (ex. : `resoc_n1`).

### Complétion du Code
1. Compléter les fichiers `news.php`, `admin.php`, `settings.php`, etc., en suivant les instructions des commentaires.

### Refactorisation
1. Identifier les sections de code répétitives et les centraliser à l’aide de `include` pour faciliter la maintenance. 

## Utilisation
Pour accéder à l’application, lancer votre serveur et accéder à l’URL suivante dans votre navigateur : `http://localhost:[port]/resoc_n1/news.php`.
