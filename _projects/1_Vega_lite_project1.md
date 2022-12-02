---
name: Final Project Part 3.1, Visualization 
image: https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pngkey.com%2Fmaxpic%2Fu2q8o0q8y3i1o0e6%2F&psig=AOvVaw3FhPpLix8hukFZJsGwZNf7&ust=1670048022467000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCMjN-eqj2vsCFQAAAAAdAAAAABAJ
description: This is our Final Project consisting of 3 dashboards.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Final Project Part 3.1, Data Viz
### Link to Python file: 

<div class="right">
{% include elements/button.html link="https://github.com/achuri2/achuri2.github.io/blob/43b8e2792e0c749f185fc34589000000950fab31/Churi_Akshant-Malik_Smit-Choudhari_Samruddhi-assignment10.ipynb" text="Python Jupyter Notebook" %}
</div>


## Drag and Select Bars on 1st Plot to Interact With 2nd Plot

DASHBOARD 1

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Area chart - Age of people involved in crash
2. Pie chart - Male Vs Female involved in crash
3. Chicago basemap - Highlights red light, speed violations, crashes in the city of Chicago
4. Line Chart - Shows monthly change in the number fo crashes

Chart 1 here is interactive and the user can easily select any range of age that the user is interested in and simultaneously the other three charts will get updated. Based on chart 1 we can see that crashes are the maximum for ages 25-30 and after selecting this particular area we can see that crashes were more for male than female with slightly more numbers. Here in chart 3 we can see that most of the crashes are associated in downtown region and some of them are spread out in south region as well. It also has a lot of red light and speed violations. In chart 4 we can see that crashes are less in Jan, Feb, March, December and maximum in the month of october. The main reason behind this can be that end and start of the year there is a lot of snow due to which people do not travel a lot with their vehicles. And october being holiday season people use a lot of vehicles leading to more crashes. 


<vegachart schema-url="{{ site.baseurl }}/assets/json/file1.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/file2.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/file3.json" style="width: 100%"></vegachart>


<div class="right">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="link to data" %}
</div>

