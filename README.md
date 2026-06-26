# ✍️ PHP Professional Blog

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

> Un blog professionnel complet développé en **PHP pur** (sans framework) utilisant l'architecture **MVC**.

Ce projet a été réalisé dans le but de démontrer mes compétences en développement backend PHP. Il comprend une partie publique pour les visiteurs et un espace d'administration sécurisé pour la gestion des articles et des commentaires.

## 🚀 Fonctionnalités

*   **Visiteurs :**
    *   Consultation des articles (blog posts).
    *   Formulaire de contact fonctionnel.
    *   Ajout de commentaires (soumis à validation).
*   **Administration (Sécurisée) :**
    *   Création, modification et suppression d'articles.
    *   Modération des commentaires (validation/rejet).
    *   Système d'authentification robuste (prévention XSS, CSRF, Injection SQL).

## 🛠️ Technologies Utilisées
*   **Backend :** PHP (Architecture MVC)
*   **Base de données :** MySQL
*   **Frontend :** HTML5, CSS3, Bootstrap
*   **Templating :** Twig (optionnel/selon implémentation)
*   **Outils :** Composer

## ⚙️ Installation (Avec Docker)
C'est la méthode recommandée. Elle configure automatiquement PHP 8.1, Apache, MySQL et importe la base de données.

1. Cloner le dépôt : `git clone https://github.com/Marc-Alban/php-professional-blog.git`
2. Aller dans le dossier du projet : `cd php-professional-blog`
3. Lancer l'environnement Docker :
   ```bash
   docker-compose up -d --build
   ```
4. Accéder au site sur `http://localhost:8080/`

La base de données est automatiquement importée avec la structure requise au démarrage.

## ⚙️ Installation (Manuelle - WAMP/XAMPP)
1. Cloner le dépôt et placer les fichiers dans votre dossier `www` ou `htdocs`.
2. Installer les dépendances : `cd Code && composer install`
3. Renommer `Code/config.ini.info` en `Code/config.ini` et configurer vos identifiants de base de données.
4. Importer le fichier `Sql/blog.sql` dans votre base MySQL.
