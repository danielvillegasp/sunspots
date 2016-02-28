---
title       : Sunspots and Temperature
subtitle    : An Explorative Analisys of Sunspot Count and Earth Temperature
author      : Daniel Villegas
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

--- 
## Introduction

Some have claimed that global warming may be due to phenomena that take place in the 
sun rather than to the carbon monoxide emissions produced by humans in the modern world.

Here, an exploratory analisys of the data is done, seeking for evidence that might help
further job to prove whether solar activity in fact has an impact over earth temperature.

--- 
## Solar Activity

Many cycles that happen in the sun have been identified. Solar rotation occurs every 24.47 earth 
days on average; sunspots maxima occur on average every 11 years.

<img src="assets/fig/sunspot-count-1.png" title="plot of chunk sunspot-count" alt="plot of chunk sunspot-count" style="display: block; margin: auto;" />

---
## Land-Ocean Temperature Index

To get the big picture of how temperature is behaving on earth with respect to time, 
scientists created the LOTI which averages the temperature over a grid on the surface of the 
earth and compare it to a logn term average of temperatures over the past years. The difference
between this two quantities is the LOTI.

LOTI is behaving has been growing for the last century, as show in the trend line.

<img src="assets/fig/loti-plot-1.png" title="plot of chunk loti-plot" alt="plot of chunk loti-plot" style="display: block; margin: auto;" />

---
## Comparison between Sunspots and LOTI
<img src="assets/fig/loti-sp-1.png" title="plot of chunk loti-sp" alt="plot of chunk loti-sp" style="display: block; margin: auto;" />

---
## Acknowledgements

Information from the following websites was used to create this presentation, I want to 
thank the people who have been working hard to collect and analize this data.

1. [Marshall Space Flight Center](http://solarscience.msfc.nasa.gov)
2. [Goddard Institute for Space Studies](http://data.giss.nasa.gov/gistemp/)
