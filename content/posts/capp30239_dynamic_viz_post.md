+++
date = '2026-01-04'
draft = false
title = 'Visualizing Great Lakes iron ore shipping'
tags = ["Data viz", "Writing"]
featured_image = "/img/post_img/interactive_project_screenshot.png"
featured_image_alt = "CAPP30239 interactive viz project"
featured_image_link = "https://hnmns.github.io/Interactive-Visualization-Project/"
featured_image_hover = "Go to project"
+++

An **interactive** data visualization project. Click the image to head to my first crack at a "scrollytelling" article. Apparently, most of the USA's iron and steel comes out of the Great Lakes region.

<!-- {{< figure
  class="media-right"
  src="/img/post_img/interactive_project_screenshot.png"
  alt="CAPP30239 interactive viz project"
  link="https://hnmns.github.io/Interactive-Visualization-Project/"
  caption=""
  class="ma0 w-75"
  width=500
>}} -->

<!--more-->

**Tools used**: MapLibre, D3, Scrollama

<hr>

### What I Learned

When I [interned with the Great Lakes Governors and Premiers](/posts/gsgp_internship_post), I got my first glimpse at the scale and importance of the Great Lakes Maritime Transportation System (MTS). I really did have trouble believing that nearly all US domestically produced iron comes from a pretty concentrated corner of the country. From the start to the finish of preparing this article, I picked up some valuable bits and pieces, such as what data the US Army Corps of Engineers actually discloses on maritime cargoes

On the computer-technical side, I got to try my hand at mapping and animation in a web article. For being a "data visualization" project, I did not get to showcase a ton of data (not an excuse, but national security got in the way of my original plan), but I *did* get to showcase the narrative that I roughly had in mind, which is still a victory on its own. Despite the limited data, I think I was just starting to build the storied ***intuition*** on D3 from what I did get to visualize. That included animating a real ship route from Duluth-Superior to Gary as the article played out.

Beware: Once in a great while, I will open the project and the interactive elements will simply not trigger until I refresh the page. I am still unsure what exactly is going on there, but just know that it is solved with an `F5`.