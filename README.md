# Modélisation : Recettes de cuisine

## Ta mission

- 🧁 Créer les diagrammes nécessaires pour modéliser une application qui stocke des recettes de cuisine

<details><summary>Extension VSCode</summary>
  Deux extensions à installer pour VSCode :

  - PlantUML
  - PlantUML Simple Viewer

</details>

## Description

### Contexte

On souhaite créer un site de recette de cuisine dont :

- N'importe qui puisse...
  - afficher la liste des recettes
  - filtrer la liste des recettes en fonction d'un ingrédient
  - afficher le détail d'une recette
- Une personne connectée puisse...
  - ajouter une recette en favori

### Information sur nos données

Une recette de cuisine a :
- un nom
- une description
- une durée de préparation
- une durée de cuisson
- un niveau de difficulté (i.e. difficile, moyen ou facile)

Pour chaque recette, on souhaite savoir quels sont les ingrédients nécessaires et la quantité associée à chaque ingrédient.  
Chaque ingrédient a un type (e.g. "féculent" pour l'ingrédient pomme de terre).


## Étape 1 : Diagramme de Cas d'Utilisation

Crée un fichier [plantUML](https://plantuml.com/fr/use-case-diagram) pour faire le diagramme de Cas d'Utilisation.

## Étape 2 : Diagramme Entités - Associations

Crée un fichier [plantUML](https://plantuml.com/fr/ie-diagram) pour faire le diagramme Entités Associations à partir des éléments suivants :

- Recette
- Ingrédient
- Type d'ingrédient

## Étape 3 : Diagramme de Séquence

Modélise l'ajout en favoris d'une recette à l'aide d'un diagramme de Séquence.

Nous sommes dans le cas d'un site utilisant un front en JS, un back sous forme d'API et une BDD postgresql.

L'information d'ajout en favoris est stockée en BDD.

## Étape 4 : Diagramme d'Activité

Réalise le diagramme d'Activité pour l'ajout en favoris.

Si une recette est déjà en favoris, cela va la retirer des favoris.
