---
title: "README.md"
output: github_document
---
## Shiny Application: Records for Hits in MLB
### The assignment for "Developing Data Products" in Data Science Specialization

This project generated visualized all-time hits record in Major League Baseball since 1871 to 2015. Data was limited to players whose hits record are above 2800. 

The raw data was acquired from [seanlahman.com](http://www.seanlahman.com). If you are interested in analyzing on your own, you can download from my repository or directly from [here](http://www.seanlahman.com/baseball-archive/statistics/). The copyright 1996-2016 belongs to Sean Lahman.  

The visualized results can be viewed from here: [https://eufmike.shinyapps.io/Records_for_Hits_in_MLB/](https://eufmike.shinyapps.io/Records_for_Hits_in_MLB/). 

### Brief Guidance
The visualized plot was generated by rCharts::nPlot, which utilized NVD3 for plotting and interaction. Users can explore the data by changing the total hits and observe the growing hits number for each player. Record of cumulative hits was plotted by year, age and the time they played for teams in MLB. The fourth chart demonstrated their batting average across their career. 

It is important to mention that NVD3 is not ideal for handle this type of data with data points over a thousand, so please be patient when you try to include all players into the charts.

© Chien-cheng Shih 2016 All Rights Reserved.