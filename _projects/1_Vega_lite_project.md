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
## select 1st graph bars to interact with 2nd graph

This is the visualization with 2 graphs. The First graph shows the average of total floors with respect to various Agencies. Graph 1 is a bar chart with color added to bar which shows the average Square footage. As seen Department of revenue seems to have highest avg total floors and square footage. Meanwhile, graph 2 shows the median square footage for various bldg status. The 1st graph is interactive on selecting bars which changes the values in the 2nd graph.
<vegachart schema-url="{{ site.baseurl }}/assets/json/file.json" style="width: 100%"></vegachart>

