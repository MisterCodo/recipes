---
title: "Title for your recipe"
recipe_image: {{ .Site.Params.front.defaultImage | default "images/defaultImage.png" }}
image_width: {{ .Site.Params.front.defaultImageWidth | default 512 }}
image_height: {{ .Site.Params.front.defaultImageHeight | default 512 }}
date: {{ .Date }}
tags: ["tag1", "tag2"]
servings: 4
prep_time: #in minutes, can be BLANK
cook: true # If cooking leave true, if cooling set to false
cook_increment: minutes # set to minutes or hours
cook_time: #in minutes or hours, can be BLANK
calories: #in kcal, can be BLANK
---

## Ingrédients

- First Ingredient
- Second Ingredient [^1]

## Instructions

1. Step One
   1. Sub Step One
2. Step Two
3. Step Three

## Notes

[^1]: Footnote 1
