🏋️ Gym Management Application

Technologies utilisées :
Cette application est une plateforme complète de gestion de gym permettant aux utilisateurs de :

Réserver des séances de sport en ligne ou en présentiel.

Acheter des produits dans la boutique.

Participer à des événements sportifs.

Découvrir les coach(s) disponibles.

🚀 Fonctionnalités

📅 Réservation de séances : en ligne ou en présentiel, gestion des horaires et disponibilité.

👨‍🏫 Gestion des coachs : profils, spécialités et planning.

🛒 Boutique en ligne : produits sportifs, gestion des stocks et commandes.

🎉 Événements : participation aux événements, notifications et rappels.

🛠️ Administration : gestion des utilisateurs, coachs, produits et séances, tableau de bord.

🏗️ Architecture

Frontend Desktop : JavaFX pour une interface fluide et interactive.

Backend : Symfony REST API pour gérer les données avec MySQL.

Base de données : MySQL pour stocker utilisateurs, séances, commandes, produits, événements et coachs.

⚡ Installation

Cloner le repository :

git clone https://github.com/ton-utilisateur/nom-du-projet.git


Configurer MySQL avec le script fourni (database.sql).

Configurer le backend Symfony :

composer install
php bin/console doctrine:migrations:migrate
symfony server:start


Lancer le frontend JavaFX depuis votre IDE ou via un JAR exécutable.

🤝 Contributions

Les contributions sont les bienvenues !
Merci de respecter les bonnes pratiques JavaFX, Symfony et MySQL.
