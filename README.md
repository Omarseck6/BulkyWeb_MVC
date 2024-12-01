# BulkyBookWeb

BulkyBookWeb est une application web de gestion de livres permettant la gestion des livres via une interface administrateur et la consultation des livres via une interface client. Ce projet est conçu pour fournir une solution complète pour la gestion et la consultation de livres.

## Fonctionnalités

### Partie Administrateur
- Ajouter de nouveaux livres.
- Mettre à jour les informations des livres existants.
- Supprimer des livres.
- Gérer les catégories et auteurs des livres.

### Partie Client
- Consulter les livres disponibles.
- Rechercher des livres par titre, auteur ou catégorie.

## Technologies utilisées

- **Backend** :
  - .NET Core
  - C#
  - Entity Framework (EF)
  - LINQ
- **Frontend** :
  - Angular
  - JavaScript
  - HTML & CSS
  - Bootstrap
- **Base de données** :
  - Microsoft SQL Server
- **Environnement de développement** :
  - Microsoft Visual Studio
  - GitHub
  - Git

## Prérequis

- [.NET SDK](https://dotnet.microsoft.com/download) version 6.0 ou supérieure.
- [Node.js](https://nodejs.org/) et npm pour Angular.
- Microsoft SQL Server.
- Visual Studio 2022 ou supérieur.

## Installation

1. Clonez le repository :
   ```bash
   git clone https://github.com/votre-utilisateur/BulkyBookWeb.git
   cd BulkyBookWeb
   ```

2. Configurez la base de données :
   - Assurez-vous que Microsoft SQL Server est en cours d'exécution.
   - Modifiez la chaîne de connexion dans `appsettings.json` avec les informations de votre base de données.

3. Appliquez les migrations pour initialiser la base de données :
   ```bash
   dotnet ef database update
   ```

4. Installez les dépendances Angular :
   ```bash
   cd ClientApp
   npm install
   ```

5. Lancez l'application :
   ```bash
   cd ../
   dotnet run
   ```

6. Ouvrez votre navigateur à l'adresse suivante : [http://localhost:5000](http://localhost:5000).

## Structure du projet

- **ClientApp/** : Frontend Angular pour la partie client.
- **Controllers/** : Contrôleurs API REST.
- **Models/** : Modèles de données.
- **Data/** : Contexte et migrations de la base de données.
- **Views/** : Vues Razor pour le backend administrateur.

## Contribution

Les contributions sont les bienvenues ! Suivez ces étapes :

1. Forkez le repository.
2. Créez une nouvelle branche :
   ```bash
   git checkout -b feature/ma-nouvelle-fonctionnalite
   ```
3. Faites vos modifications et validez-les :
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin feature/ma-nouvelle-fonctionnalite
   ```
5. Ouvrez une Pull Request.

## Auteur

- **Omar Seck**

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
