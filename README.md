🏫 Pension App

Pension App est une application web de gestion scolaire moderne conçue pour simplifier la gestion des élèves, des classes et des paiements de pension dans les établissements scolaires.
Elle permet d’automatiser les tâches administratives, de sécuriser les données et de centraliser toutes les informations dans une seule interface intuitive.

🚀 Fonctionnalités principales

👨‍🎓 Gestion des élèves : inscription, modification, suivi et exportation des données.

🏫 Gestion des classes : création et organisation des classes avec leurs effectifs.

💰 Suivi des paiements : enregistrement des paiements, génération de reçus, exportation CSV.

🔐 Authentification sécurisée avec JWT (JSON Web Tokens).

⚙️ Interface administrateur via Flask-Admin.

🌍 API REST basée sur Flask et SQLAlchemy.

📦 Migration de base de données avec Alembic.

🔄 Webhooks pour automatiser certaines intégrations (paiement, notification, etc.).

☁️ Déploiement prêt avec Gunicorn et environnement configurable (.env).

🛠️ Technologies utilisées

Python 3 + Flask — Framework web léger et rapide.

PostgreSQL — Base de données relationnelle robuste.

Flask_SQLAlchemy — ORM pour interagir avec la base de données.

Marshmallow — Sérialisation et validation des données.

Flask-JWT-Extended — Gestion de l’authentification par jetons.

Flask-CORS — Autorisation des requêtes depuis le front-end.

Passlib — Hachage sécurisé des mots de passe.

Alembic — Migrations de base de données.

Gunicorn — Serveur WSGI pour le déploiement.

📈 Objectif

Créer une solution complète et fiable pour les établissements scolaires souhaitant :

Moderniser leur gestion administrative,

Éviter les erreurs de saisie,

Gagner du temps dans le suivi des paiements et des élèves,

Centraliser toutes leurs données en ligne.