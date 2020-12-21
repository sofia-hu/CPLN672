---
title: "Are some areas becoming more dangerous"
date: 2020-12-21
published: true
tags: [dataviz, ml, folium]
excerpt: "A machine learning analysis"
hv-loader:
  hv-chart-1: "charts/chierror_map.html"
  hv-chart-2: "charts/nyerror_map.html"
folium-loader:
  folium-chart-1: ["charts/foliumchi2020", "400"]
  folium-chart-2: ["charts/foliumchi2019", "400"]
  folium-chart-3: ["charts/foliumny2020", "400"]
  folium-chart-4: ["charts/foliumny2019", "400"]
toc: true
toc_sticky: true
---

# Chicago

This section built a machine learning method to predict crash patterns in Chicago.

## Machine Learning Results

We used the 2019 crash counts, total population and median household income to predict the 2020 crash counts in each census tract. The overall prediction accuracy was 0.82 (with best hyper parameters). Below is a choropleth map of the prediction error (%) of crashes in each census tract:

<div id="hv-chart-1"></div>

## A closer look into Tract 100600

We paid extra attention to where the crash count increased from 2019 to 2020. Since total traffic decreased significantly after pandemic, such unusual increase may offer some unique understanding of crash patterns. We filtered the test set for census tracts with increase of crashes, and ranked them for the tract with most prediction error (i.e., most unusual increase). This analysis brought us to Tract 100600, a residential area. Below is a choropleth map of the crash index in this area. Note that there are some changes from 2019 to 2020:

<div id="folium-chart-1"></div>

<div id="folium-chart-2"></div>

# New York

This section built a machine learning method to predict crash patterns in Brooklyn borough, New York.

## Machine Learning Results

We used the 2019 crash counts, total population and median household income to predict the 2020 crash counts in each census tract. The overall prediction accuracy was 0.85 (with best hyper parameters). Below is a choropleth map of the prediction error (%) of crashes in each census tract:

<div id="hv-chart-2"></div>

## A closer look into Tract 260900

We paid extra attention to where the crash count increased from 2019 to 2020. Since total traffic decreased significantly after pandemic, such unusual increase may offer some unique understanding of crash patterns. We filtered the test set for census tracts with increase of crashes, and ranked them for the tract with most prediction error (i.e., most unusual increase). This analysis brought us to Tract 260900, a residential area. Below is a choropleth map of the crash index in this area. Note that there are some changes from 2019 to 2020:

<div id="folium-chart-3"></div>

<div id="folium-chart-4"></div>
