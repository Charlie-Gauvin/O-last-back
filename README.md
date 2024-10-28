# API Backend - Projet de Titre Professionnel - Développeur Web et Web Mobile

Ce projet est une API développée en groupe dans le cadre de notre certification pour le titre professionnel de Développeur Web et Web Mobile. Nous avons conçu cette API en suivant les principes du CRUD et en utilisant des requêtes SQL pures avec PSQL pour la gestion de la base de données.

## 📋 Description du projet

Le but du projet est de pouvoir mettre en lien plusieurs joueurs de jeux vidéos pouvant se créer des profils de jeu et poster des annonces en ligne afin de que les joueurs puissent se mettre en relation et jouer ensemble sur des jeux vidéo. L'API permet de Create, Read, Update et Delete des annonces et des profils.

## 🛠️ Technologies et outils utilisés

- Langage : JavaScript
- Framework : Express
- Base de données : PostgreSQL avec des requêtes SQL pur
- ESlint : Pour assurer une propreté et une cohérence dans le code
- Docker et Docker Compose : Environnements de travail communs à tous limitant considérablement les bugs.

## 🔐 Sécurité

Plusieurs couches de sécurité ont été mises en place pour assurer la protection des données et des utilisateurs :

- CORS : Contrôle les accès à l'API
- bcryptjs : Hachage et sécurisation des mots de passe des utilisateurs
- dotenv : Permet de gérer les variables d'environnements
- jsonwebtoken : Génerer et valider les tokens d'authentification
- pg : gérer les connexions sécurisées à la base de données

## 📂 Architecture du projet

Une architecture a été mises en place afin de faciliter la gestion et la maintenance du projet :

- controllers : Contient la logique métier de l'application
- models : gère les requêtes SQL vers la base de données
- middlewares : gère les différentes vérifications concernant la sécurité de l'application
- routes : Définit les routes et points de terminaison de l'API
