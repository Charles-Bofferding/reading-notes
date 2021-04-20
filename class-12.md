# 201 Course Notes

## 4/20/2021 201

# *HTML canvas and JS Chart*

**JS Chart**
- This is a tool that helps make graphs and such on your webpage.
- Setup involves downloading the library into your working folder and calling it with: 

  ```html
  <script src='Chart.min.js'></script>
  ```
- It requires you to also setup a canvas element in the body of your html
  ```html
  <canvas id="buyers" width="600" height="400"></canvas>
  ```
- Use something similar to this code in the footer 
  ```html
  <script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
  </script>
  ```
- Both pie charts and bar charts can be made with this method. See examples at this [website](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

**HTML Canvas**
- [w3 schools canvas reference](https://www.w3schools.com/graphics/canvas_reference.asp)
- A canvas element is similar to a picture element in how it is defined
- There are many shapes that can be drawn on the canvas with automatic tools. Refer to the reference page at the start of this section to see them listed.
- The 'pen' of the drawing tool can be moved without drawing lines to create new shapes in the same canvas.
- Transparency, fill, gradient, and line widths can all be applied to the things drawn on the canvas.
- Text can also be input on the canvas.

[Go Back](README.md)

[Hard Link to this Full Live Page](https://charles-bofferding.github.io/reading-notes/class-12.html)