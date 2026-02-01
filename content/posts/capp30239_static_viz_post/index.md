+++
date = '2025-11-12T13:57:26-06:00'
draft = false
title = 'Native American gaming and reservation wealth'
tags = ["Data viz", "Writing"]
featured_image = "/img/post_img/narrative_screenshot.png"
featured_image_alt = "CAPP30239 static viz project"
featured_image_link = "native-gaming-narrative-singlepage.pdf"
featured_image_hover = "Go to repo"
+++

A **static** data visualization project. I've heard no shortage of opinions about casinos and Indian Country in my lifetime, mostly indignant or condescending. This is my broad overview of the alleged relationship between tribal gaming ownership and economic outcomes, investigated through charts.

<!--more-->

<!-- {{< figure
  src="/img/post_img/narrative_screenshot.png"
  alt="CAPP30239 static-viz project"
  link="https://github.com/hnmns/Static-Visualization-Project.git"
  caption=""
  class="ma0 w-75"
  width=500
>}} -->

**Tools used**: Vega-Altair, Camelot

<hr>

### My Methods

The National Indian Gaming Commission registers all tribally owned gaming facilities and reports them in a PDF. I converted the jagged PDF to a CSV and tallied up the number of unique gaming facilities owned by each nation. Tribal gaming revenues belong solely to the nations themselves, so the numbers and types of facilities were probably the next best proxy measurement for revenues. 

An exploratory data analysis by charts is already such a far cry from a randomized experiment, so I couldn't fret too much about demonstrating a profound connection between gaming revenue and economic outcomes. All I really could hope to accomplish was showing that it is not, in fact, obvious that a casino or two is all it takes to lift a community out of hardship. This is not a very exciting or groundbreaking conclusion, but I still think it is important to give attention to the state of Native American and reservation populations.

<!-- [Download the full report (PDF)](native-gaming-narrative-singlepage.pdf) -->

### Data Narrative Report

<iframe
  src="./native-gaming-narrative-singlepage.pdf"
  width="100%"
  height="600px"
  style="border: none;"
></iframe>