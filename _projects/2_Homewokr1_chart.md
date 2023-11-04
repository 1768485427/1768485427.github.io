---
name: homework8 chart
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# homewokr chart 1


## Chart1.0
<vegachart schema-url="{{ site.baseurl }}/assets/json/year_square_footage.json" style="width: 100%"></vegachart>
For this graph, audiences can view the relationship betweent the year of these buildings contructed with the square footage depends on cities.Audiences can searh their prefer cities to review the relationship. The encoding type that I am using is the rectangular heatmap. The color of bin represents the density of count of records. The color more close to blue has a high density and close to yellow presents a low density. For the data transformation, I am using the transform_calculate, using the log_pop to transform the data. I use two interactive ways. One is brush. It can allow users to select the range. And another interactive ways is the dropdown. This can let users to choose what kinds of cities they want to use.
## Chart2.0
<vegachart schema-url="{{ site.baseurl }}/assets/json/use_status_chart.json" style="width: 100%"></vegachart>
For this graph, audiences can view the relationship betweent the total floors with the square footage depends on the bldg status.Audiences can searh the prefer status of Bldge whether it is in use, abandon or in progress. The encoding type that I am using is the rectangular heatmap. The color of bin represents the density of count of records. The color more close to blue has a high density and close to yellow presents a low density. For the data transformation, I am using the transform_calculate, using the log_pop to transform the data. I use two interactive ways. One is brush. It can allow users to select the range. And another interactive ways is the dropdown. This can let users to choose what status of the Bldg.
<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv"  text="The Data"%}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/1768485427/1768485427.github.io/blob/main/assets/json/use_status_chart.json" text="The Analysis" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/1768485427/1768485427.github.io/blob/main/assets/json/year_square_footage.json" text="The Analysis" %}
</div>
