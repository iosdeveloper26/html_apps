# Diet & Recipe Manager

A modern web application for tracking meals and managing your favorite recipes. Keep tabs on your daily calorie intake while building and organizing a personal recipe collection.

## Features

- **Recipe Management**: Create, edit, and delete recipes with detailed nutritional information
- **Meal Logging**: Log meals throughout the day with timestamps
- **Daily Dashboard**: View real-time statistics including total recipes, today's meals, and daily calorie totals
- **Nutritional Tracking**: Track calories, protein, and carbohydrates per recipe
- **Ingredients & Instructions**: Store detailed ingredients and cooking instructions for each recipe
- **Local Storage**: All data is saved locally in your browser—no account or cloud sync needed

## Getting Started

1. Open `index.html` in a web browser
2. Click **Add Recipe** to create your first recipe
3. Enter recipe details: name, calories, servings, protein, carbs, ingredients, and instructions
4. Use **Log Meal** to record recipes you've eaten throughout the day
5. View your daily statistics in the dashboard at the top

## How to Use

### Adding a Recipe

1. Click the **Add Recipe** button
2. Fill in the recipe form:
   - **Recipe Name**: The name of your dish
   - **Calories**: Total calories per serving
   - **Servings**: Number of servings this recipe makes
   - **Protein (g)**: Grams of protein (optional)
   - **Carbs (g)**: Grams of carbohydrates (optional)
   - **Ingredients**: List each ingredient on a new line
   - **Instructions**: Cooking instructions
3. Click **Save Recipe**

### Logging a Meal

1. Click **Log Meal** in the "Today's Meals" section
2. Select a recipe from the dropdown
3. Set the time you ate the meal
4. Click **Log Meal**

The meal will appear in your daily log with the meal time and calorie count.

### Editing a Recipe

1. Locate the recipe card in the Recipes section
2. Click **Edit** to modify the recipe
3. Update any fields and click **Save Recipe**

### Deleting a Recipe or Meal

1. For recipes: click **Delete** on a recipe card
2. For meals: click **Remove** on a meal entry in today's log
3. Confirm the deletion when prompted

## Dashboard Statistics

The dashboard displays three key metrics:

- **Total Recipes**: Count of all recipes you've created
- **Today's Meals**: Number of meals logged today
- **Today's Calories**: Total calorie count for today's logged meals

## Data Storage

All recipes and meal logs are stored in your browser's local storage. Your data persists between sessions but is specific to this browser and device. Clearing your browser cache will erase all data.

## Technical Details

- **Built with**: HTML5, CSS3, JavaScript (Vanilla)
- **Storage**: Browser localStorage API
- **Design**: Dark mode UI with responsive grid layout
- **Compatibility**: Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## Tips

- Organize recipes by meal type (breakfast, lunch, dinner, snacks) using the recipe name
- Log meals soon after eating to keep accurate daily totals
- Update recipe information if nutritional values change
- Use the ingredients list to plan grocery shopping

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

Enjoy tracking your diet and managing your recipes!