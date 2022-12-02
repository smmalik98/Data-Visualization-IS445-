---
name: Final Project Part 3.1, Visualization 
image: https://user-images.githubusercontent.com/98044494/205228244-231c2043-aa79-4f71-8f1f-6252b16057a6.png
description: This is our Final Project consisting of 3 dashboards.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# CHICAGO VEHICLE CRASH ANALYSIS, Data Viz
# Project done by Akshant Churi, Samruddhi Choudhari & Smit Malik
### Link to Python file: 

<div class="right">
{% include elements/button.html link="https://github.com/achuri2/achuri2.github.io/blob/0e4a98c01b7b8cf4edc35020ebfcae87a835323b/main%20analysis.ipynb" text="Python Jupyter Notebook" %}
</div>


## BACKGROUND
The Chicago city crashes are on the rise and it is really important to analyse the issues related to this. This project aims to analyze these crashes with respect to weather, car models, red light violations, speed violations and otehr factors. This project can help the user as well as chicago government to see what areas are more prone to crashes, what car models are mostly involved in thses crashes and what weather conditions affect these the most.

## DASHBOARD 1: Drag and Select Bars on 1st Area Plot to Interact With the rest 3 charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Area chart - Age of people involved in crash
2. Pie chart - Male Vs Female involved in crash
3. Chicago basemap - Highlights red light, speed violations, crashes in the city of Chicago
4. Line Chart - Shows monthly change in the number fo crashes

Chart 1 here is interactive and the user can easily select any range of age that the user is interested in and simultaneously the other three charts will get updated. Based on chart 1 we can see that crashes are the maximum for ages 25-30 and after selecting this particular area we can see that crashes were more for male than female with slightly more numbers. Here in chart 3 we can see that most of the crashes are associated in downtown region and some of them are spread out in south region as well. It also has a lot of red light and speed violations. In chart 4 we can see that crashes are less in Jan, Feb, March, December and maximum in the month of october. The main reason behind this can be that end and start of the year there is a lot of snow due to which people do not travel a lot with their vehicles. And october being holiday season people use a lot of vehicles leading to more crashes. 


<vegachart schema-url="{{ site.baseurl }}/assets/json/file1.json" style="width: 100%"></vegachart>

## DASHBOARD 2: Drag and Select Bars on 1st Area Plot to Interact with the rest 2 charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Bar chart - Types of cars models involved in crashes
2. Line chart - Crash trend over years 2016-2022 
3. Bar Chart - Shows the amount of damange done(in $) (501-1500$) and (over 1500$)

This is an interactive dashboard where once the user selects the car models he is interested in the rest 2 charts get updated. Based on the charts we can see that Camry model car had the maximum number of crashes followed by accord. Maybe these are the cars that people own the most and affordable ones. After selecting camry in the furst plot we can see that it had maximum accidents in year 2017 and then it dropped during the covid years since there were less people out on roads driving. And based on chart 3 we can see that most of the damage was over 1500$ which means there were serious damage done to the car. This can be beneficial in understanding the areas these accidents happended the most while if the car models were not safe enough to drive.


<vegachart schema-url="{{ site.baseurl }}/assets/json/file2.json" style="width: 100%"></vegachart>

## DASHBOARD 3: Drag and Select Bars on 1st bar plot to Interact With the rest 3 bar charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Bar Chart - Monthly crash count
2. Bar Chart - Weather crash count
3. Bar Chart - Lightening crash count
4. Bar Chart - Roadway crash count

This dashboard has 4 charts that are linked to each other. They help the user understand the monthly crash count along with the weather, lightening and roadway conditions. Based on chart 1 we can see that month of september, october had maximum crashes and followed by winter season having the least. In claer weather conditions we have had the maximum crashes while in daylight lightening condition. Also when the road was dry the accidents happened the most. Hence, we can see that weather plays an important role in crashes across Chicago.





<vegachart schema-url="{{ site.baseurl }}/assets/json/file3.json" style="width: 100%"></vegachart>


<div class="right">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="link to data" %}
</div>

