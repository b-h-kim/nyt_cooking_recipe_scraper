# NYT Cooking Recipe Scraper

## Overview
The goal of the NYT Cooking Recipe Scraper is to export recipes from the New York Times Cooking website and save them in a YAML format compatible with the Paprika 3(recipe managing app). It is crucial to emphasize that this script is strictly intended for personal use only. 

### Python Libraries
Before using the NYT Cooking Recipe Scraper, make sure you have the following Python libraries installed:
- pandas
- Beautifulsoup 4
- Requests library
- YAML library
- Base64 library

## YAML recipe Format
YAML multiple recipes example:

```bash
name: My Tasty Recipe
servings: 4-6 servings
source: Food Network
source_url: http://www.google.com
prep_time: 10 min
cook_time: 30 min
on_favorites: yes
categories: [Dinner, Holiday]
nutritional_info: 500 calories
difficulty: Easy
rating: 5
notes: |
  This is delicious!!!
photo: (base-64 encoded image)
ingredients: |
  1/2 lb meat
  1/2 lb vegetables
  salt
  pepper
  2 tbsp olive oil
  4 cups flour
directions: |
  Mix things together.
  Eat.
  Tasty.
  Yum yum yum.
 ```
 
## Legal Disclaimer
This script is strictly intended for personal use only and is meant to be used in conjunction with a valid subscription to the New York Times. Please respect the terms of service and usage policies of the New York Times Cooking website. The author of this script is not responsible for any misuse or unauthorized distribution of scraped content.
