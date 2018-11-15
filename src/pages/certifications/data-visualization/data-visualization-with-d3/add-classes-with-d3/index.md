---
title: Add Classes with D3
---
## Add Classes with D3
In D3, the `attr` takes two arguments. The first is the element's attribute type, the second is it's value.

### Spoiler
```html
<style>
  .bar {
    width: 25px;
    height: 100px;
    display: inline-block;
    background-color: blue;
  }
</style>
<body>
  <script>
    const dataset = [12, 31, 22, 17, 25, 18, 29, 14, 9];
    
    d3.select("body").selectAll("div")
      .data(dataset)
      .enter()
      .append("div")
      // Add your code below this line
      .attr("class", "bar")
      // Add your code above this line
  </script>
</body>
```

### Resources
[D3 Attributes](https://github.com/d3/d3-selection/blob/master/README.md#selection_attr)
