---
name: Homework 10, Visualization 
image: https://icons.veryicon.com/png/o/business/chart-icon/visualization-icon-07-07.png
description: This includes the 2 charts 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Homework 10, Data Viz
## Drag and Select Bars on 1st Plot to Interact With 2nd Plot

This visualization has 2 plots which are interconnected to each other. The first plot shows the average of total floors with respect to the buildings acquired by different Agencies. Plot 1 shows the average Square footage of buildings acquired by the Agencies using bar plots. The density of these floors are calculated by aggregating the total floors for each agency with respect to the building they have acquired over the years and these are shown using a color theme. It can be observed that the Department of Revenue has highest average total floors but still the median square footage is not the highest. Meanwhile, the plot 2 shows the median square footage of different buildings acquired by the agencies which have different Building Status. To make it more interesting we have made these plots interlinked to each other. This can be done dragging and selecting the bars of the first plot. Based on the area you have dragged, the median square footages for different buildings (acquired by selected agencies) with different status get updated on the second plot. 
The idea and the code has been taken from Assignment 9 (https://starboard.gg/nb/noPXJg6). It did not have any interactivity before, but we have introduced it in this.
<vegachart schema-url="{{ site.baseurl }}/assets/json/file.json" style="width: 100%"></vegachart>

