# Recipe Food

> **Note:** This is a repository showcasing my specific contributions to a group project. The complete source code is hosted in the original team repository (linked below).

## 1. Project Overview
An Android application that allows users to browse and search for thousands of cooking recipes via a remote API. Key features include viewing detailed ingredients, cooking instructions, and saving favorite recipes for offline access.

## 2. My Role & Key Contributions
I served as the **Database & Local Storage Developer**, responsible for implementing robust on-device data persistence.

### Key Responsibilities:
* **Local Database Design:** Leveraged **Android Room Database** to design entities for storing recipe details and user preferences.
* **Offline "Favorites" Feature:**
    * Implemented a caching mechanism: Tapping "Favorite" saves the complete recipe data from the API into the local Room database.
    * Ensured the "Saved Recipes" list remains accessible even without an internet connection.
* **Query Optimization:** Developed efficient DAOs (Data Access Objects) for smooth CRUD operations (Create, Read, Update, Delete) without blocking the main UI thread.

## 3. Key Technologies
* **Language:** Java (Android Native)
* **Database:** Room Database (SQLite)

## 4. Link to Original Repository
The full project source code is managed here:
* **Original Repo:** https://github.com/Hoangvu2911/recipe_food_app

---
