---
title: "Illinois Building Inventory Visualizations"
---

## Chart 1: Number of Buildings by Illinois Agency


This chart shows how many buildings are owned by each agency. I used the Building Inventory dataset and grouped the data by “Agency Name” to track the number of buildings per agency. Grouping by agency helped transform a long, overwhelming list of individual buildings into a summarized format that shows the varying sizes of footprints by agency.

In terms of design choices, I used a bar chart to keep the visualization simple and clear for comparison. The x-axis shows the number of buildings (quantitative), and the y-axis lists each agency (nominal). I sorted the bars from largest to smallest so it’s easy to see which agencies own the most properties quickly. I didn’t apply a color scheme here, the focus is more on the numbers than differentiating between agency. Overall, the goal of this plot is to provide a quick overview of how building ownership is spread across different agencies.

<vegachart schema-url="{{harshithavet.github.io}}/assets/json/chart1.json" style="width: 100%"></vegachart>

---

## Chart 2: Number of Buildings per County (Filtered by Agency)

This interactive chart dissects how each agency’s buildings are spread across counties in Illinois. It filters the data by whatever agency the user chooses from the dropdown menu. I used the count() function to calculate how many buildings each agency has in one county, which helps further segment the overall totals from Chart 1 into location-specific information. 

In terms of design choices, I used a bar chart again because it’s an easy way to compare building counts across counties. The x-axis shows the number of buildings (quantitative) and the y-axis lists counties (nominal) instead of agency this time. I used color to distinguish each county and kept the default Altair color scheme since the focus is mainly on comparing bar lengths. The interactive dropdown is what makes this chart more interesting it lets the viewer compare and contrast any agency, like “University of Illinois” vs. “Department of Transportation,” and instantly see which counties have the most buildings for that agency. This interactivity makes it easier to explore the data in more detail and with more customization. 


---

### Links
- [The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv)
- [The Analysis](https://github.com/harshithavet/harshithavet.github.io/blob/master/python_notebooks/buildings.ipynb)
