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

## ⚙️ Installation
1. Cloner le dépôt : `git clone https://github.com/Marc-Alban/php-professional-blog.git`
2. Installer les dépendances : `composer install`
3. Configurer la base de données (importer le script SQL fourni).
4. Lancer le serveur local PHP ou utiliser WAMP/XAMPP/Docker.
