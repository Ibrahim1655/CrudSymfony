# 🎓 Mon apprentissage Symfony

Petit repo pour m'exercer sur Symfony en dehors des cours.

Je suis étudiant en **BUT MMI** (Métiers du Multimédia et de l'Internet), parcours **Développement Web et Dispositifs Interactifs**.
On commence officiellement Symfony au **Semestre 3** , mais j'ai voulu creuser le sujet de mon côté pour ne pas être perdu et comprendre comment fonctionne un framework MVC.

##  Ce que contient ce projet
C'est un exercice classique : un **CRUD** pour gérer un annuaire de personnes.

J'ai utilisé :
*   **Symfony** (la base)
*   **Twig** pour les vues
*   **Tailwind CSS** pour le design (j'ai essayé de faire un truc propre sans que ce soit trop compliqué)
*   Une base de données MySQL (via XAMPP)

##  Pour lancer le projet
Petit mémo pour moi-même si je dois réinstaller le projet :

1.  Installer les dépendances : `composer install`
2.  Vérifier la connexion BDD dans le `.env`
3.  Créer la base et les tables :
    ```bash
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate
    ```
4.  Lancer le serveur : `symfony serve`

*Note : J'apprends encore, donc le code n'est peut-être pas encore parfait !*
