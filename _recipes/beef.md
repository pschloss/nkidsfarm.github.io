---
layout: default
category: recipes
type: index
title: Beef
picture: ../assets/img/patrick_pigs.jpg
---

Beef is a great source of protein. Grass-fed beef like that raised at Eight Kids Farm is even better! Here are some of our favorite beef recipes.

{% assign page_array = site.recipes | where: "type", "beef"	%}
{% include picture_grid.html pages=page_array				%}
