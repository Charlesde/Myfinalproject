# Myfinalproject

# Summary - in no more than 4 sentences, briefly introduce your data visualization and add any context that can help readers understand it

These datasets are based on electronic records of the entire bwin.party betting history of 2,068 subscribers who triggered a responsible gambling intervention between November 2008 and November 2009 (i.e. RG cases) and 2,066 individuals who made an initial bwin.party deposit on the same day as an RG case, but did not trigger a responsible gambling intervention between November 2008 and November 2009 (i.e. controls). With this scatterplot, I want to visually show that there seems to be a relation between the total stakes and the time spend on fixed odds gambling. Also, it shows that gamblers that trigger a responsible gambling intervention have more extreme scores. 

# Design - explain any design choices you made including changes to the visualization after collecting feedback

I wanted to make a scatterplot because I wanted to compare two variables while also accounting for the RG case and non RG case. and it is interesting to see the volume of the total bets/losses which could be the size of the bubbles. As it turns out, the size just makes it confusing and we need a zoom function to see the relation between the x and y axis. Also, changes were made in the variables (stakes instead of bets) and in the explanations.

Because the respondents all commented on the extreme RG scores, I added a line to emphasize this notion.

# Feedback - include all feedback you received from others on your visualization from the first sketch to the final visualization

Resp 1:
- Would be cool if you could zoom in
- Refrain from making RG red and other green, no moral judgement.
- Make a zoom function so that we can see the relation better.
- Add a better graph title
- Why gambling data? Motivation for choosing this topic.
- Main takaway: RG gamblers are for more extreme.

Resp 2:
- rename labels so that it is not 1 and zero anymore
- Maybe a nice background color

Resp 3:
- Remove the ouliers (zoom in)
- add text in graph to explain your line better.
- Add explanatory text below graph
- remove the z dimension (bubble size), it is confusing and too much information
- RG gamblers seem extreme

# Resources - list any sources you consulted to create your visualization

This data can be downloaded from http://www.thetransparencyproject.org/download_index.php. 
https://stackoverflow.com/questions/25416063/title-for-charts-and-axes-in-dimple-js-charts
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
http://ggplot2.tidyverse.org/reference/labs.html
https://github.com/d3/d3-transition
