### Système de Gestion de Café – Étude de Cas (TypeScript)
 Description du projet
Ce projet est une simulation d’un système de gestion pour un café, développé en TypeScript. Il permet de :

Gérer les différentes commandes de café.

Ajouter dynamiquement des personnalisations (comme du lait, du sucre, etc.).

Suivre les ingrédients disponibles dans l’inventaire.

Sauvegarder les données localement à l’aide de IndexedDB.

Utiliser des concepts avancés comme les Design Patterns (Singleton, Factory, Decorator) et le modèle DAO pour organiser l’accès aux données.

L’objectif de ce projet est de construire un système modulaire, maintenable et testable, tout en respectant des contraintes de conception modernes.

#### Fonctionnalités principales
Création de différents types de café (Espresso, Latte, Cappuccino) via une fabrique (factory).

Ajout de personnalisations sans modifier les classes de base grâce au pattern Decorator.

Stockage des commandes et des ingrédients dans IndexedDB.

Utilisation de promesses et de async/await pour gérer les opérations asynchrones.

Une seule instance du gestionnaire d'inventaire (InventoryManager) via le pattern Singleton.

Structure du code claire avec séparation en DAO, modèles, services, etc.

### Résultat obtenu
Lors de l'exécution du projet, voici un exemple de sortie affichée dans la console :
Coffee Beans in inventory: 100
Order saved: {
  coffee: Coffee { id: 1, name: 'Espresso', size: 'Small', price: 2.5 },
  customizations: [
    Customization { name: 'Milk', price: 0.5 },
    Customization { name: 'Sugar', price: 0.2 }
  ],
  date: '2025-04-11T21:01:05.121Z'
}
