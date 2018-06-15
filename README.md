# oo-many-practice-cook-recipe

# COOKS, RECIPES, RECIPE_CARDS

 - A recipe has many cooks through recipe_cards
 - A cook has many recipes through recipe_cards
 - A recipe_card belongs to a recipe and an cook

* Each Recipe has a name and cuisine
* Recipe#recipe_cards
* Recipe#cooks
* Recipe#new_recipe_card (makes new recipe_card for user)
* Recipe.least_popular
* Recipe.find_by_cuisine

===================================

* Each Cook has a name
* Cook#recipe_cards
* Cook#recipes
* Cook#write_recipe (makes new recipe_card for recipe)
* Cook.most_active_cook => returns the cook who has most recipe_cards for recipes

===================================

* Each recipe_card has an cook and a recipe
* RecipeCard#Cook
* RecipeCard#Recipe
