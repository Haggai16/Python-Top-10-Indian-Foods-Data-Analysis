
# Indian Food Dishes Analysis
## Overview
This project involves a comprehensive analysis of various Indian dishes as described in the indian_food.csv dataset. It aims to explore the diversity in Indian cuisine across different dimensions such as diet type, cooking and preparation times, flavor profiles, and regional distributions.

## Dataset Description
The dataset comprises details on 255 Indian dishes with the following attributes:

- name: Name of the dish.
- ingredients: List of main ingredients used.
- diet: Type of diet (vegetarian or non-vegetarian).
- prep_time: Preparation time in minutes.
- cook_time: Cooking time in minutes.
- flavor_profile: Flavor category of the dish (e.g., sweet, spicy).
- course: Type of course (e.g., dessert, main course).
- state: Indian state where the dish is popular.
- region: Region of India the dish is from.

## Data Handling
Initial data inspection is followed by handling missing values and errors in numerical entries (such as '-1' values replaced with NaN for clarity).

## Analysis
Key aspects of the analysis include:

- Proportions of vegetarian vs. non-vegetarian dishes.
- Distribution of cooking and preparation times.
- Analysis of the most common ingredients via word clouds.
- Exploration of dishes by flavor profiles and regions.

## Visualization
Graphical visualizations are provided through:

- Pie charts for dietary distribution.
- Bar plots for dishes with the shortest and longest cooking times.
- Interactive plots using Plotly for detailed exploration.
