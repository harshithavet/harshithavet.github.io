---
name: Homework 5
tools: [Python, Altair, VegaLite]
description: My submission for HW5!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Chart 1

<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl.json" style="width: 100%"></vegachart>

This chart shows how many buildings are owned by each agency. I used the Building Inventory dataset and grouped the data by “Agency Name” to track the number of buildings per agency. Grouping by agency helped transform a long, overwhelming list of individual buildings into a summarized format that shows the varying sizes of footprints by agency.

In terms of design choices, I used a bar chart to keep the visualization simple and clear for comparison. The x-axis shows the number of buildings (quantitative), and the y-axis lists each agency (nominal). I sorted the bars from largest to smallest so it’s easy to see which agencies own the most properties quickly. I didn’t apply a color scheme here, the focus is more on the numbers than differentiating between agency. Overall, the goal of this plot is to provide a quick overview of how building ownership is spread across different agencies.


# Chart 2

<vegachart schema-url="{{ site.baseurl }}/assets/json/visualization.vl.json" style="width: 100%"></vegachart>

This chart shows how many buildings are owned by each agency. I used the Building Inventory dataset and grouped the data by “Agency Name” to track the number of buildings per agency. Grouping by agency helped transform a long, overwhelming list of individual buildings into a summarized format that shows the varying sizes of footprints by agency.

In terms of design choices, I used a bar chart to keep the visualization simple and clear for comparison. The x-axis shows the number of buildings (quantitative), and the y-axis lists each agency (nominal). I sorted the bars from largest to smallest so it’s easy to see which agencies own the most properties quickly. I didn’t apply a color scheme here, the focus is more on the numbers than differentiating between agency. Overall, the goal of this plot is to provide a quick overview of how building ownership is spread across different agencies.

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/harshithavet/harshithavet.github.io/blob/master/python_notebooks/buildings.ipynb" text="The Analysis" %}
</div>
