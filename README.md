# RecipeMatch+

RecipeMatch+ is a relational SQL database project that recommends recipes based on ingredients available in a user's pantry.

## Features

* Recipe recommendation based on available ingredients
* Recipe rating and bookmarking
* Ingredient category hierarchy
* Pantry management system

## Database Design

The database follows Third Normal Form (3NF) and includes the following main entities:

User
Recipe
Ingredient
IngredientCategory
RecipeIngredient
RecipeStep
Pantry
Rating
Bookmark

## Technologies

SQL
Relational Database Design
Database Normalization (3NF)

## Project Context

Developed as part of a **Database Systems course project**.

## Database Structure

The database includes the following main entities:

- USERS
- RECIPE
- INGREDIENT
- INGREDIENT_CATEGORY
- PANTRY
- RECIPE_STEP
- STORED_IN
- RECIPE_INGREDIENT
- BOOKMARK
- RATING

The project also includes:

- SQL Views for recipe match scoring
- SQL Views for rating summaries
- Triggers for automatic timestamp updates and data validation
