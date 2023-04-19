# Gestion-de-livres

initialiser votre projet
>symfony new Books

 lancer le serveur de Symfony
>symfony server:start

Le premier outil est le maker-bundle. Cela permet de demander à Symfony de nous créer certains éléments via la ligne de commande
>composer require symfony/maker-bundle --dev

Pour interagir avec une base de données, Symfony utilise ce qu’on appelle un ORM (Object Relational Mapping)
>composer require orm

Créez l’entité Book
>php bin/console make:entity

créer votre base grâce à Doctrine
>php bin/console doctrine:database:create

transformer l’entité en véritable table
>php bin/console doctrine:schema:update --force

#Ajoutez des fixtures 

installer fixtures
>composer require orm-fixtures --dev (Ctrl + Shift + P)
>composer require doctrine/doctrine-fixtures-bundle --dev

exécuter fixtures
>php bin/console doctrine:fixtures:load

#Créez votre première route

créer notre première route
>php bin/console make:controller

#Serializer

installer
>composer require symfony/serializer-pack





