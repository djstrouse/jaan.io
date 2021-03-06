---
layout: post-light-feature
title: The Statistics of Recipes
description: "What is special about the small fraction of ingredient combinations that we use as recipes?"
category: project
modified: 2014-01-20
tags: [statistics, recipes, information theory, entropy, culturomics, projects]
comments: true
image:
  thumb: recipentropy.jpg
---

This project started with a riddle:

"Can you think of three foods for which each pair tastes good together, but the combination of all three does not?"

If you're stumped, don't feel bad - I've never heard a good example. (Though the most entertaining, rumored to have originated with a student at UC-Berkeley, is "a shot of tequila, a shot of tequila, a shot of tequila.")

Subjectivity in what "tastes good" aside, this riddle begs the question: can you construct recipes simply by combining ingredients that taste good as pairs? Or do you need to consider three, four, or more ingredients at once? Does this vary by recipe type? By culture?

Perhaps surprisingly, these questions can be formalized in a rigorous, quantitative way. Using the framework of [maximum](http://www.nature.com/nature/journal/v440/n7087/full/nature04701.html) [entropy](http://www.princeton.edu/~wbialek/rome/lecture3.htm) [modeling](http://en.wikipedia.org/wiki/Principle_of_maximum_entropy), we can ask how much of the information contained in the distribution of recipes is accounted for by pairwise interactions alone, and how much depends on triplet, quadruplet, or higher order interactions. Using a [database](http://www.nature.com/srep/2011/111215/srep00196/full/srep00196.html#supplementary-information) containing over 50,000 recipes (and over 300 ingredients), we are attempting to answer these questions, as well as predict new recipes.

<strong>With: [Ari Strandberg-Peshkin](https://sites.google.com/site/arianasp/home) & Kelsi Lindblad</strong>

This project description was adapted from one by [Ari Strandberg-Peshkin.](https://sites.google.com/site/arianasp/projects/recipentropy)