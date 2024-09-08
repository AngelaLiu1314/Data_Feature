Data Feature: Calorie Counter

The purpose of this data feature is to provide a recipe and calorie information to a user given a main ingredient.

This data feature combines two APIS:
1. EDAMAN Recipie API(https://developer.edamam.com/edamam-docs-nutrition-api)
2. EDAMAN Nutrition Analysis API(https://developer.edamam.com/edamam-docs-recipe-api)

First, this data feature prompts users for 1 ingredient. Then the program runs the ingredient through the EDAMAN recipe API to find the top recipe. 

Second, this data feature will analyze the ingredients from the recipe and then calculate the calories from this recipe.

Finally, this data feature will return the top recipe, its ingredients, and the calories for the recipe.

The user can keep inputting ingredients until they find a recipe that they want.
