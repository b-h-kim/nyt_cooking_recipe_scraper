# NYT Cooking Recipe Scraper

## Overview
The goal of the NYT Cooking Recipe Scraper is to export recipes from the New York Times Cooking website and save them in a YAML format compatible with the Paprika 3(recipe managing app). It is crucial to emphasize that this script is strictly intended for personal use only. As a subscriber to the New York Times, this script allows you to access recipes you have legal access to through your subscription.

## Python Libraries
The following Python libraries are used in this project:

Beautifulsoup 4
Requests library
YAML library
Base64 library

## YAML recipe Format
YAML multiple recipes example:

  name: My Tasty Recipe
  servings: 4-6 servings
  source: Food Network
  source_url: http://www.google.com
  prep_time: 10 min
  cook_time: 30 min
  nutritional_info: 500 calories
  on_favorites: yes
  categories: [Dinner, Holiday]
  difficulty: Easy
  rating: 5
  notes: |
    This is delicious!!!
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
  
## Legal Disclaimer
This script is strictly intended for personal use only and is meant to be used in conjunction with a valid subscription to the New York Times. The scraping process is performed with the intention of accessing recipes you have legal access to as a subscriber. Please respect the terms of service and usage policies of the New York Times Cooking website. The author of this script is not responsible for any misuse or unauthorized distribution of scraped content.
