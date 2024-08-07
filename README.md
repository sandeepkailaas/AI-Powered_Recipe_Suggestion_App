# AI-Powered_Recipe_Suggestion_App

Building AI course project

## Summary
The AI-Powered Recipe Suggestion System provides personalized recipe recommendations based on the ingredients users have available. This helps in meal planning, reducing food waste, and optimizing ingredient usage.

## Background
Many people face the challenge of deciding what to cook with the ingredients they have, leading to food waste and inefficient meal planning. This project aims to solve these common issues by suggesting recipes based on the available ingredients.
Reduces food waste by suggesting recipes for available ingredients.
Simplifies meal planning by providing instant recipe ideas.
Optimizes ingredient usage, ensuring nothing goes to waste.

## How is it used?

Users input a list of ingredients they have on hand, and the system generates a list of recipes that can be made with those ingredients. The solution is particularly useful in everyday meal planning and for individuals looking to reduce food waste. Primary users are home cooks and individuals seeking meal planning assistance.

      +------+
      | Start|
      +------+
          |
          v
 +-----------------+
 | Collect Ingredients |
 +-----------------+
          |
          v
 +----------------------+
 | Do you have all      |
 | the ingredients?     |
 +----------------------+
         / \
       /     \
     v        v
+--------+ +----------------+
|  Yes    | | No (Get missing |
| Proceed | | ingredients)    |
+--------+ +----------------+
         |
         v
+----------------------+
| Mix Ingredients      |
+----------------------+
         |
         v
+----------------------+
| Bake at 350 degrees  |
+----------------------+
         |
         v
+----------------------+
| Cool & Serve         |
+----------------------+
         |
         v
     +------+
     | End  |
     +------+


## Data sources and AI methods

The project utilizes data from open recipe APIs such as Spoonacular and TheMealDB. Key AI techniques include:
Natural Language Processing (NLP): To process and understand ingredient lists.
Recommendation Algorithms: To suggest recipes based on the processed ingredient data.

## Challenges
The project does not solve:
Ingredient Variability: Different forms of ingredient input need to be normalized.
Recipe Quality: The quality and relevance of suggested recipes depend on the dataset.
Data Availability: Limited or biased data can affect the system's performance and accuracy.

## What next?
Future improvements could include:
Enhanced Recommendations: Improve the recommendation algorithm to consider user preferences and dietary restrictions.
Customization: Allow users to save favorite recipes and create shopping lists.
Integration: Integrate with grocery delivery services for ingredient purchases.
Community Contributions: Enable users to add and share their recipes, improving the dataset.

## Acknowledgments
Inspired by existing recipe recommendation systems on cooking websites and apps.
Used open source libraries like NLTK for NLP and Surprise for recommendation algorithms.
