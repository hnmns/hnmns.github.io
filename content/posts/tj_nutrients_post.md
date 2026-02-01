+++
date = '2025-07-10T00:46:36-05:00'
draft = false
title = "TJ's Nutrients-per-dollar Investigation"
tags = ["Data viz", "Personal"]
featured_image = "/img/post_img/tj_calorie_per_dollar.png"
featured_image_alt = "Grocery product nutrient viz"
featured_image_link = "https://github.com/hnmns/tallying-joules.git"
featured_image_hover = "Go to repo"
+++

Exploring nutrition facts and prices at a certain grocery chain. My excuse to try out Streamlit so I can say that I've used it (and because it's helpful [and to min-max my grocery shopping]).

<!--more-->

**Tools used**: Streamlit, Polars, Vega-Altair, GraphQL

<hr>

### The Impetus

Paul Prudhomme wanted us to know that

> "You don't need a silver fork to eat good food."

I tend to agree, and in the spirit of [offloading more cognitive functions to the technology of the day](https://www.historyofinformation.com/detail.php?id=3439), I wanted to make a tool to figure out which grocery items nourish well by the dollar. By "nourish," I really just mean "be high in calories and protein" (for my own purposes).

[Here](https://github.com/cmoog/traderjoes) is where I first found out about the TJ's product info API that I used.

### The Findings

Some preliminary findings include that, to no surprise, oil-laden foods like cooking oil and peanut butter give you quite a few calories for your dollar. Flour was also up there.

Annoyingly, there were many instances of individually wrapped and boxed items (e.g. snack bars) whose data were entered in terms of the full box quantity *except* for the price. This made for a bunch of high-value red herrings. I may have to come back to this project with some sort of outlier detection model.

I am considering ways to make the Streamlit app quickly accessible and actually useful for a consumer. Something more in the vein of "enter a product name, get a Yes/No result on whether it's a value purchase." I would love for my work stay out of the dreaded Data Dashboard Graveyard, where well-intentioned "data tools" never earn the attention of real-life human beings.

<!-- {{< figure
  src="/img/post_img/tj_calorie_per_dollar.png"
  alt="TJ nutrient investigation"
  link="https://github.com/hnmns/tallying-joules"
  caption=""
  class="ma0 w-75"
  width=500
>}} -->