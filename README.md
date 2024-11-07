CookBuds - Recipe Explorer App
Welcome to CookBuds, a Flutter app designed for food enthusiasts to discover, explore, and save delicious recipes from various cuisines worldwide. CookBuds offers a curated selection of recipes categorized by cuisine, with features to search, like, and view detailed instructions. Get ready to cook up something amazing!

Key Features
Login Page: A welcoming screen to validate user access. Users enter a mock username and password to access the app (for demo purposes).
Cuisine Browser: Browse an extensive list of cuisines, from Italian and Japanese to Indian and more. Each cuisine contains multiple unique recipes.
Search Functionality: A search feature allows users to find a specific cuisine quickly, enhancing user experience and making navigation easy.
Recipe Details: For each recipe, detailed information on ingredients and step-by-step instructions are provided.
Favorite Recipes: Users can like recipes and view them in a dedicated "Liked Recipes" page, creating a personalized list of favorite recipes.
Seamless Navigation: Navigate effortlessly between pages with intuitive transitions and actions.

Project Structure

This Flutter app is divided into multiple classes for modularity and simplicity:
1. Main Entry Point
main.dart: The entry point for the app, initializing MyApp, which sets up the theme and home page.
2. Login Page
LoginPage Class: A stateful widget allowing users to enter credentials. Upon successful login, users are directed to the RecipePage.
Error Handling: Simple validation prompts an error message if the username and password are incorrect.
3. Recipe Models
Recipe Class: Encapsulates each recipe’s details, including name, ingredients, and instructions.
Cuisine Class: Represents a cuisine category containing a list of recipes.
4. Pages
RecipePage: The main page listing all cuisines. Tapping a cuisine directs users to CuisineRecipePage, where recipes for the selected cuisine are displayed.
CuisineRecipePage: Lists all recipes for a selected cuisine, enabling users to dive into specific recipes.
RecipeDetailsPage: Displays a selected recipe's ingredients and instructions. Users can also mark recipes as favorites.
LikedRecipesPage: Contains all recipes that the user has liked, providing easy access to their favorite dishes.
5. Search Functionality
CuisineSearchDelegate: Implements a search feature for cuisines, filtering based on the user’s query and returning matching results.
6. Helpers
showLikeSnackbar: Helper function to provide feedback when users like or unlike a recipe.
Usage Instructions
Run the app: After cloning the repository, open the project in an IDE with Flutter support, like VS Code or Android Studio, and run flutter run in the terminal.
Login: Use the credentials "user" and "password" (for demonstration purposes only).
Browse and Search: Explore cuisines and recipes, or use the search bar to quickly find a specific cuisine.
Like and Save Recipes: Mark recipes as favorites to easily access them later in the "Liked Recipes" section.


Future Enhancements
User Authentication: Integrate Firebase or another backend for real user authentication.
Persistent Storage: Save liked recipes locally or in the cloud for access across sessions.
More Cuisines and Recipes: Expand the database of recipes for a richer experience.
Advanced Search: Allow users to search by recipe name, ingredients, or other keywords.
Personalized Recommendations: Suggest recipes based on users' liked dishes.
