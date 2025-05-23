# 📘 Projet JavaFX – Gestion de Projets Collaboratifs

Ce projet est une application de bureau JavaFX permettant de **gérer des utilisateurs, des cours et des séances** dans le cadre d’un emploi du temps collaboratif.

## 🧩 Fonctionnalités

### 👤 Utilisateurs
- CRUD (Créer, Lire, Mettre à jour, Supprimer)
- Rôles (ENSEIGNANT, ÉTUDIANT, ADMINISTRATEUR)
- Association et dissociation aux cours

### 📚 Cours
- Création/modification/suppression
- Gestion des périodes de cours (début/fin)
- Liaison avec utilisateurs et séances
- Export CSV des participants

### 📅 Séances
- Titre, description, date limite
- Statut (TODO, IN_PROGRESS, DONE)
- Priorité (Oui/Non)
- Affichage en tableau, vue Kanban et vue calendrier
- Liées à un cours

## ⚙️ Technologies utilisées
- Java 2025
- JavaFX 24
- MySQL + JDBC
- Architecture MVC

## 📁 Structure du projet

```
src/
├── controller/        # Contrôleurs JavaFX
├── model/             # Modèles métiers
├── dao/               # Accès aux données (MySQL)
├── database/          # Connexion JDBC
└── Main.java          # Point d'entrée
resources/
└── fxml/              # Interfaces graphiques
```

## 🚀 Lancer le projet

1. Lancer MySQL et créer la base `gestionprojets`
2. Importer le script SQL fourni
3. Modifier `DatabaseConnection.java` si besoin :
```java
private static final String URL = "jdbc:mysql://localhost:3306/gestionprojets";
private static final String USER = "root";
private static final String PASSWORD = "";
```
4. Ouvrir et exécuter `Main.java`
## 🧑🏽‍💻 Réalisé par

- **Ange Nolwen DJUISSI KENMOE**
- **Ivan Remy SIMO MENDJE** 

Dans le cadre du module **II.1102 – Algorithmique et Programmation Java** à l'**ISEP**.

