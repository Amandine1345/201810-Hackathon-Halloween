# Hackathon Halloween

C’est Halloween, tu as revêtu ton plus beau costume et tu pars sonner aux 
maisons autour de chez toi pour récupérer un maximum de bonbons !
 
Mais tu es un gourmand collectionneur, et cette année, tu les veux tous ! 
Heureusement, tu viens de commencer ta formation à la Wild et tu vas 
pouvoir coder une petite application pour t’aider ! 

## Objectif

Proposer une démo fonctionnelle, dans un temps limité, en respectant les
consignes données:
* Utiliser l'API [OpenFoodFacts](https://en.wiki.openfoodfacts.org/API) pour récupérer une liste de bonbons
* Utiliser l'API [adresses](https://adresse.data.gouv.fr/api) (et/ou la géolocalistion HTML)

* Durée du projet : 28 heures

![Le Bonbondex](https://drive.google.com/uc?export=view&id=13NCEzvkrNJd_LfRARFuLReqEBu138pHm)

## Installation

1. Cloner le dépôt GitHub.
2. Taper la commande `composer install`.
3. Créer *app/db.php* à partir de *app/db.php.dist* et ajouter les paramètres de votre base.
```php
define('APP_DB_HOST', 'your_db_host');
define('APP_DB_NAME', 'your_db_name');
define('APP_DB_USER', 'your_db_user_wich_is_not_root');
define('APP_DB_PWD', 'your_db_password');
```
4. Créer une nouvelle base sur le serveur local et importer le fichier `data/201810-Hackathon-Halloween.sql`.
5. Lancer votre serveur local `php -S localhost:8000 -t public/`.
6. Lancer [http://localhost:8000/database](http://localhost:8000/database), depuis votre navigateur, pour remplir la base de données.
7. Tester l'application !

### Langages
* HTML 5
* CSS 3
* Bootstrap 4
* PHP 7

### Versionning
* Git

### Réalisé avec
* PhpStorm
 
#### Contributeurs

* Patricia Batjorm - [PBAT75](https://github.com/PBAT75)
* Guillaume Gallier - [Guisharko](https://github.com/Guisharko)
* Mathieu Hoarau - [Mathelchrist](https://github.com/Mathelchrist)
* Teddy Milon - [milonte](https://github.com/milonte)
* Amandine Turpin - [Amandine1345](https://github.com/Amandine1345)