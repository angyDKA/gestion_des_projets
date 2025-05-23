
# 📋 Gestion de Tâches Collaboratives

Application JavaFX de gestion de projets, de tâches et d’employés développée dans le cadre du module II.1102 – Projet Algorithmique et Programmation Java à l'ISEP.

## 🚀 Présentation

Cette application a pour objectif de faciliter la coordination d’équipe, la planification des projets et le suivi des tâches au sein d’une plateforme intuitive. Elle centralise les données liées aux projets, employés et tâches dans une base de données **MySQL (via phpMyAdmin)**.

## 🛠️ Fonctionnalités

- **Gestion des employés** : ajout, modification, suppression via interface JavaFX
- **Gestion des projets** : création, assignation de membres, dates de début/fin
- **Gestion des tâches** :
  - Affectation à un employé
  - Priorité, date limite, statut
  - Vue **Kanban**
  - Vue **Calendrier**
- **Sauvegarde automatique** : données persistantes via base MySQL
- **Architecture modulaire (MVC)** : séparation des vues (FXML), contrôleurs, modèles et DAO

## 📁 Architecture du projet

```
src/
├── com.monapp.controller    # Contrôleurs JavaFX (interactions UI)
├── com.monapp.model         # Classes métier : Employe, Projet, Tache, StatutTache
├── com.monapp.dao           # Accès à la base de données (CRUD via JDBC MySQL)
├── com.monapp.database      # Connexion MySQL via DatabaseConnection
└── Main.java                # Point d’entrée JavaFX
```

## 🧱 Technologies utilisées

- Java 17+
- JavaFX + FXML
- MySQL (via phpMyAdmin)
- JDBC
- Maven
- IntelliJ IDEA

## 🗃️ Base de données

- Utilise **MySQL** (géré via phpMyAdmin)
- Script SQL fourni pour la création des tables
- Connexion via `DatabaseConnection.java`

## 📌 Exemples d’améliorations envisagées

- 🔔 Notifications de deadline
- 🔐 Authentification multi-utilisateurs
- ☁️ Hébergement cloud multi-accès
- 💬 Chat intégré & partage de documents

## 📷 Interfaces

- Gestion des employés : tableau éditable
- Gestion des projets : planification + membres
- Gestion des tâches : vue Kanban + calendrier

## 🧑🏽‍💻 Réalisé par

- **Ange Nolwen DJUISSI KENMOE**
- **Ivan Remy SIMO MENDJE** 

Dans le cadre du module **II.1102 – Algorithmique et Programmation Java** à l'**ISEP**.

