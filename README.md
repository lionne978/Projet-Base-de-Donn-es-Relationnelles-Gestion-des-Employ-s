# Projet-Base-de-Donn-es-Relationnelles-Gestion-des-Employ-s
# **Employee Database Management Project**

Ce projet consiste à concevoir et manipuler une base de données relationnelle pour gérer les informations des employés, des services et des localisations dans une organisation.

## **Objectifs**
1. Concevoir une structure relationnelle robuste pour organiser les données des employés.
2. Implémenter des tables avec des clés primaires et étrangères pour assurer l'intégrité des données.
3. Écrire et optimiser des requêtes SQL pour effectuer des opérations courantes et produire des analyses utiles.

## **Fonctionnalités Principales**

### **1. Création et Gestion des Tables**
- Définition des tables pour les employés, services et localisations.
- Ajout de clés primaires et étrangères pour établir les relations entre les entités.
- Mise en place de contraintes pour garantir la cohérence des données.

### **2. Manipulation des Données**
- **Insertion** : Ajout de données pour les employés, services et localisations.
- **Filtrage** : Utilisation de conditions pour récupérer des données spécifiques.
- **Regroupement** : Création de rapports groupés (par département, localisation, etc.).
- **Calculs** : Réalisation d'opérations simples (totaux, moyennes, etc.).

### **3. Optimisation et Analyse**
- Écriture de requêtes complexes pour extraire des informations utiles.
- Analyse des statistiques sur les effectifs, la répartition des employés par département, etc.

## **Exemples de Requêtes SQL**
1. Liste des employés par département.
2. Nombre d'employés par localisation.
3. Salaire moyen des employés par service.
4. Recherche d'employés dont le salaire est supérieur à une valeur donnée.

## **Technologies Utilisées**
- **SQL** : Langage pour créer et manipuler la base de données.
- **SGBD** : MySQL

## **Structure des Fichiers**
- `create_tables.sql` : Script pour créer les tables avec clés primaires et étrangères.
- `insert_data.sql` : Script pour insérer les données initiales.
- `queries.sql` : Requêtes pour les opérations courantes et les analyses.

## **Installation et Configuration**
1. Importer le fichier `create_tables.sql` dans votre SGBD.
2. Charger les données à l'aide du script `insert_data.sql`.
3. Exécuter les requêtes du fichier `queries.sql` pour tester et explorer les données.
