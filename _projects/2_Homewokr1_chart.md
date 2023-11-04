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


## Chart1
<vegachart schema-url="{{ site.baseurl }}/assets/json/year_square_footage.json" style="width: 100%"></vegachart>

## Chart2
<vegachart schema-url="{{ site.baseurl }}/assets/json/use_status_chart.json" style="width: 100%"></vegachart>

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/1768485427/1768485427.github.io/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>


