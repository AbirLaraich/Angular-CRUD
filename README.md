# Application de Gestion des Utilisateurs avec Angular

## Description

Il s'agit d'une Application à Page Unique (SPA) développée avec Angular, conçue pour une gestion utilisateur complète intégrant des pratiques modernes de développement web. L'application offre des fonctionnalités CRUD (Création, Lecture, Mise à Jour, Suppression) complètes pour les données utilisateur, s'appuyant sur une API fictive et incorporant les meilleures pratiques du développement Angular.

## 🌟 Fonctionnalités

### Gestion des Utilisateurs
- Gestion complète du cycle de vie des utilisateurs
- Interface intuitive pour créer, lire, mettre à jour et supprimer des enregistrements utilisateur
- Manipulation de données en temps réel avec programmation réactive

### Fonctionnalités Avancées
- **Pagination**: Navigation efficace dans les ensembles de données utilisateur
- **Internationalisation**: Changement dynamique de langue
- **Design Responsive**: Mise en page adaptée aux appareils mobiles
- **Expérience Utilisateur Riche**: Interface interactive et fluide

## 🛠 Stack Technique

### Technologies Principales
- **Framework Frontend**: Angular
- **Gestion d'État**: Observables RxJS
- **Styling**: 
  - Bootstrap (Design Responsive)
  - FontAwesome (Icônes)
- **Internationalisation**: @ngx-translate/core

### Bibliothèques et Dépendances Principales
- Angular Core
- RxJS
- Bootstrap
- FontAwesome
- ngx-translate

## 📦 Structure du Projet

### Composants
1. **HeaderComponent**
   - Affiche la barre de navigation supérieure
   - Gère le menu déroulant de sélection de langue

2. **MenuComponent**
   - Fournit les liens de navigation à l'échelle de l'application
   - Sert de hub de navigation central

3. **UserListComponent**
   - Affiche un tableau complet des utilisateurs
   - Supporte des actions en ligne :
     * Édition des détails utilisateur
     * Suppression des enregistrements utilisateur
   - Implémente des contrôles de pagination

4. **UserFormComponent**
   - Formulaire dynamique pour la saisie de données utilisateur
   - Supporte les workflows de création et de mise à jour
   - Implémente la validation de formulaire

### Services
#### UserService
- Gère toutes les interactions HTTP
- Gère le cycle de vie des données utilisateur
- Implémente les opérations CRUD
- Utilise RxJS pour les flux de données asynchrones

## 🚀 Démarrage

### Prérequis
- Node.js (version 14.x ou ultérieure)
- Angular CLI
- npm (Node Package Manager)

### Étapes d'Installation
1. Cloner le dépôt
    ```bash
    git clone https://github.com/AbirLaraich/Angular-CRUD.git
    ```

2. Installer les Dépendances
    ```bash
    npm install
    ```

3. Lancer le Serveur de Développement
    ```bash
    ng serve
    ```

4. Accéder à l'Application
   - Ouvrir un navigateur à l'adresse `http://localhost:4200`
