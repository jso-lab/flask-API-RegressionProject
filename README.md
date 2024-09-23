# An API with Flask integrated a ML model

## Avant-propos

Ce projet est un cas pratique fait en équipe au cours de ma formation de développeurn en intelligence artificielle. Il a ensuite été mis à jour et est en constante évolution. 

1. Modèle de régression

Le modèle de machine learning qui y est intégré sert à prédire le prix d'une voiture d'occasion. Il est à titre indicatif. Les annonces et les informations décrites sont purement fictives et ne sont en aucun cas des informations réelles. 

2. Confidentialité 

Le site internet qui est présenté n'est pas un site officiel. Aucune donnée ne transite à travers le site. Aucune information sensible n'y est contenu. 

## Lancement de l'application

1. Exécution en local

- Téléchargement du dépôt github contenant le projet. 
- Ouvrir un Terminal à la racine du projet et lancer la commande 
` pip install -r requirements.txt` : Cette commande installe les librairies et les dépendances du projet.
- Lancer le serveur Flask avec la commande ` waitress-serve --listen=0.0.0.0:8000 app:app` : cette commande lance le serveur [waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/index.html) sur le port 8000. Vous pouvez donc vous rendre à l'adresse `http://12.0.0.1:800` pour accéder à la page d'accueil de l'application.

## Création de compte et navigation

Pour commencer à exploiter les ressources de l'application, il faut bien sûr disposer d'un compte. Le menu indique le lien vers la page d'inscription. Une fois le compte crée, revenir à la page de connexion.

## Améliorations 

Le projet est en constante évolution et d'autres fonctionnalités viendront s'ajouter progressivement :
- fonctions des tests
- fichiers de logs
- espace utilisateurs pour enregistrer des favoris ou historique de consultations
- plus d'annonces
- page d'aide

## Crédits

[Jean-Paul SOSSAH](https://www.linkedin.com/in/jean-paul-sossah/)
