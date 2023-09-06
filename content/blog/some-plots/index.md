+++
title = "Some Plots"
date = "2023-08-15"
description = "Some plots created with Apache ECharts"
taxonomies.tags = [
    "syntax",
]
+++

The theme also has support for charts created with [Apache ECharts](https://echarts.apache.org/).

For example, here's the [Anscombe's quartet](https://en.wikipedia.org/wiki/Anscombe%27s_quartet):

{{ echarts(js_file="anscombes_quartet.js" height="500px") }}

And here's a plot of the [Klein bottle immersed in three-dimensional space](https://en.wikipedia.org/wiki/Klein_bottle):

{{ echarts(js_file="klein_bottle.js" height="500px") }}

You can see the source code to generate these plots in the [`content/blog/some-plots`](https://github.com/salcc/zola-bearplus/tree/main/content/blog/some-plots) directory of the theme's repository.
