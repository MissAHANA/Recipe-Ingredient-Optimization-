# Recipe Ingredient Optimization and Health Insights

## Overview
This project analyzes a synthetic dataset of 400 recipes to:
- Identify the **most common ingredients** in top-rated recipes.
- Explore **nutritional trends** like calories, fat, and protein.
- Find the **healthiest recipes** based on a simple health score.

The goal is to provide insights into which ingredients are both **popular and healthy**, helping optimize recipe choices.
## Dataset
- **File:** `recipe.csv`
- **Columns Included:**
  - `Name` – Recipe name
  - `Ingredients` – List of ingredients
  - `Calories`, `FatContent`, `ProteinContent`, `CarbohydrateContent`
  - `RecipeServings`, `Rating`

This dataset is **synthetic** and was generated using Python to simulate real-world recipes.

## Features
- **Ingredient Frequency Analysis:** Top 10 ingredients in high-rated recipes.
- **Health Insights:** Low-calorie and high-protein recipe detection.
- **Visualizations:** Bar charts and scatter plots for quick insights.

---

## How to Run
### **Requirements**
- Python 3.x
- Libraries:
  ```bash
  pip install pandas matplotlib
## Sample Output

### Top 10 Ingredients in Top-Rated Recipes
Top 10 Ingredients in Top-Rated Recipes:
[('almonds', 22), ('banana', 21), ('corn', 21), ('ginger', 21), ('tofu', 20),
('garlic', 20), ('cashew', 19), ('honey', 19), ('cheese', 19), ('peas', 19)]
### Calories vs Protein Content

### Top 5 Healthiest Recipes:
Top 5 Healthiest Recipes:
                Name  Calories  ProteinContent  FatContent  Rating  
203      Tangy Toast       163            38.7         1.0     3.8   
331       Zesty Bowl       214            37.8         3.6     3.7   
170      Spicy Curry       227            37.9         3.9     4.4   
283  Savory Smoothie       317            37.5         3.1     4.9   
27       Spicy Pasta       338            35.0         1.2     4.0   

## Future Improvements
1. Add cost optimization.

2. Use NLP to analyze recipe instructions.

3. Build a dashboard using Power BI or Streamlit.

## Author
Developed by Ahana Mukhopadhyay. Feel free to fork and improve this project!


