# D3_Sample

Visualizing student's height and eye color from MSiA Data Visualization course.

This project is part of an assignment for MSiA 411.

The requirements are as follows:

Write a d3.js program that will read in the attached data file and render two bar charts on a single web page.  

1. sorted by student name
2. sorted by height (high to low)

The color of each bar should represent the eye color, and the length of the bar should represent the height.  In order to make it easy to read the names, you should use a horizontal bar chart

Be sure to include a descriptive title for each chart, axes, axis label for the numeric axis, tick marks, tick labels, grid lines, and a legend for the color encoding.  Follow the design principles in the lecture notes for good chart design.

## Getting Started

This static visualization can be viewed by serving the file up for your browser via your favorite server engine.

Most simply, navigate to this directory and run:

```shell
python -m http.server
```

Then, open a browser to `localhost:8000` or whatever port the python server is running on.

_Note_: If `index.html` does not render correctly, `simple.html` has the same content but without links to googlefonts or bootstrap