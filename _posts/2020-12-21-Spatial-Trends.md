---
title: "Spatial Trends"
date: 2020-12-21
published: true
tags: [dataviz, hvplot, holoviews]
excerpt: "Spatial changes of crash patterns"
altair-loader:
  altair-chart-1: "charts/measlesAltair.json"
hv-loader:
  hv-chart-1: "charts/chitrend_map.html"
  hv-chart-2: "charts/chichange_map.html"
  hv-chart-3: "charts/nytrend_map.html"
  hv-chart-4: "charts/nychange_map.html"
toc: true
toc_sticky: true
---

# Chicago

This section examined the spatial changes of crash patterns in Chicago.

## Trend by Tract

Below is a choropleth map of the crashes in 2018, 2019 and 2020. Note that there is some difference between 2020 car crash patterns and the 2018-2019 general trends:

<div id="hv-chart-1"></div>

## Change in Pandemic

Below is a choropleth map of the change rate (%) of crashes in each census tract, from 2019 to 2020:

<div id="hv-chart-2"></div>

## Clustering

To better understand the spatial patterns of crashes, we did a clustering analysis using dbscan method in scikit-learn. Below is the clustering result (top 5 groups) in 2020:

![Chicago 2020]({{ site.url }}{{ site.baseurl }}/assets/images/chi2020cluster2.png)

Below is the clustering result (top 5 groups) in 2019. Note that there is a unique cluster in 2020 that dis not appear in 2019, which is an area of interest for us in the following section:

![Chicago 2019]({{ site.url }}{{ site.baseurl }}/assets/images/chi2019cluster.png)

# New York

This section examined the spatial changes of crash patterns in New York.

## Trend by Tract

Below is a choropleth map of the crashes in 2018, 2019 and 2020. Note that there is no significant difference between 2020 car crash patterns and the 2018-2019 general trends:

<div id="hv-chart-3"></div>

## Change in Pandemic

Below is a choropleth map of the change rate (%) of crashes in each census tract, from 2019 to 2020:

<div id="hv-chart-4"></div>

## Clustering

To better understand the spatial patterns of crashes, we did a clustering analysis using dbscan method in scikit-learn. Below is the clustering result (top 5 groups) in 2020:

![New York 2020]({{ site.url }}{{ site.baseurl }}/assets/images/ny2020cluster2.png)

Below is the clustering result (top 5 groups) in 2019. Note that the cluster patterns are significantly different from 2020:

![New York 2019]({{ site.url }}{{ site.baseurl }}/assets/images/ny2019cluster.png)
