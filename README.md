
# 🌟 Renal Disease Prediction System 🩺🔍  

Ce projet est une application web interactive permettant de prédire les maladies rénales à l'aide de modèles d'apprentissage automatique et d'un backend Django. L'objectif principal est d'offrir un outil pratique et fiable pour les professionnels de santé afin de faciliter les diagnostics précoces.

## 📌 Fonctionnalités  

- Prédiction des maladies rénales à partir des données des patients.  
- Interface utilisateur intuitive pour les médecins et les patients.  
- Gestion des comptes utilisateur (admin, médecin, patient).  
- Visualisation des résultats prédictifs et des analyses.  

## 🚀 Technologies utilisées  

- **Frontend** : HTML, CSS, JavaScript  
- **Backend** : Django Framework 🐍  
- **Machine Learning** : Modèles d'IA pour la prédiction des maladies rénales  
- **Base de données** : SQLite  
- **Environnement de développement** : Python 3.x, Virtualenv  

## 🛠️ Installation et configuration  

### Prérequis  

- Python 3.x  
- pip (gestionnaire de paquets Python)  
- virtualenv  

### Étapes  

1. Clonez le dépôt :  

   ```bash  
   git clone https://github.com/votre-repo/renal-disease-ml-django.git  
   cd renal-disease-ml-django  
   ```  

2. Configurez un environnement virtuel et installez les dépendances :  

   ```bash  
   virtualenv venv  
   source venv/bin/activate  # Sur Windows : venv\Scripts\activate  
   pip install -r requirements.txt  
   ```  

3. Configurez la base de données :  

   ```bash  
   python manage.py migrate  
   ```  

4. Créez un superutilisateur pour l'administration :  

   ```bash  
   python manage.py createsuperuser  
   ```  

5. Lancez le serveur :  

   ```bash  
   python manage.py runserver  
   ```   

## 📂 Structure du projet  

```
renal_disease/  
├── db.sqlite3                 # Base de données SQLite  
├── manage.py                  # Fichier principal pour les commandes Django  
├── renal_disease/             # Répertoire principal du projet Django  
│   ├── settings.py            # Paramètres du projet  
│   ├── urls.py                # Routes URL  
│   └── wsgi.py                # Point d'entrée WSGI pour le déploiement  
├── templates/                 # Fichiers HTML pour le frontend  
├── static/                    # Fichiers CSS, JavaScript et images  
├── models/                    # Modèles de données Django  
└── README.md                  # Documentation du projet  
```  

## 💡 Améliorations futures  

- Intégration d'un tableau de bord analytique pour suivre les tendances des diagnostics.  
- Ajout de modèles de Machine Learning plus avancés pour une meilleure précision.  
- Extension pour supporter plusieurs langues.  
- Hébergement de l'application sur un serveur de production (par ex. AWS, Heroku).  

