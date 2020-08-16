# Showing All X-Axis Values on an NVD3 multiBarChart

## Problem

I was building a multiBarChart widget with NVD3. When displayed, the bar chart x-axis only showed every other label. I wanted it to show all of the labels.

## Solution

Solution is to set the `reduceXTicks` propery on the chart to `false`

``` javascript
chart.reduceXTicks(false);
```

Not documented anywhere.