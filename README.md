# SQL-Sales-Analysis

##  Description
Ce projet propose une analyse complète des ventes à partir d'une base de données MySQL.  
Il utilise **SQL** pour les requêtes analytiques, **Python** pour la génération de datasets, et **Power BI** pour la visualisation des résultats.  
L’objectif est de mettre en évidence les tendances de chiffre d’affaires (CA), la répartition par région et par type de dossier, ainsi que les comportements clients.

---

##  Structure du projet
SQL-Sales-Analysis
│
├── data
│   └── ventes.csv              # Données brutes exportées
│
├── sql
│   └── analysis_queries.sql     # Requêtes SQL pour l'analyse
│
├── python
│   └── generate_dataset.py      # Script Python pour générer/transformer les données
│
├── dashboard
│   └── dashboard_powerbi.png    # Exemple de dashboard Power BI
│
└── README.md                    # Documentation du projet

---

## ⚙️ Fonctionnalités
- Extraction et analyse des données de ventes avec SQL.
- Génération de datasets nettoyés et enrichis via Python.
- Visualisation interactive avec Power BI :
  - CA par région
  - CA par type de dossier
  - Nombre de clients et CA moyen
  - Évolution temporelle des ventes

Préparer les données :

Importer ventes.csv dans MySQL ou utiliser le script Python pour générer un dataset.

Exécuter les requêtes SQL :

Ouvrir sql/analysis_queries.sql et lancer les requêtes dans ton SGBD.

Visualiser dans Power BI :

Charger les données préparées.

Utiliser le fichier dashboard/dashboard_powerbi.png comme référence pour construire ton rapport.
