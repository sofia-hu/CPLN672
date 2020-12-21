---
title: "General Trends"
date: 2020-12-21
published: true
tags: [dataviz, hvplot, seaborn]
excerpt: "Non-spatial changes of crash patterns"
hv-loader:
  hv-chart-1: "charts/chimonthtrend1.html"
  hv-chart-2: "charts/chimonthtrend2.html"
  hv-chart-3: "charts/chireason_chart.html"
  hv-chart-4: "charts/chiinjure_chart.html"
  hv-chart-5: "charts/chifatal_chart.html"
  hv-chart-6: "charts/nymonthtrend1.html"
  hv-chart-7: "charts/nymonthtrend2.html"
  hv-chart-8: "charts/nyreason_chart.html"
  hv-chart-9: "charts/nyinjure_chart.html"
  hv-chart-10: "charts/nyfatal_chart.html"
toc: true
toc_sticky: true
---

# Chicago

This section examined the non-spatial changes of crash patterns in Chicago.

## Total Trend

Below, we show the monthly trend of total crash counts:

<div id="hv-chart-1"></div>

Note that due to the decrease of total traffic volume, the 2020 data may be incomparable with the 2019 data, so we adjusted the crash count in terms of the total traffic volume (using the Apple Map data):

<div id="hv-chart-2"></div>

## Month & Time

Below, we show the time pattern of crashes. Note that most crashes happened in the afternoons, and there are more crashes in summer months (June, July, August):

![Chicago 2020]({{ site.url }}{{ site.baseurl }}/assets/images/chihourmonth2020.png)

There is no significant difference between the 2019 pattern and the 2020 pattern:

![Chicago 2019]({{ site.url }}{{ site.baseurl }}/assets/images/chihourmonth2019.png)

## Reason

Below, we show the top 10 reasons of crashes. Note that during pandemic (2020), there are more crashes caused by Speeding, Disregarding traffic signals and Lack of experience:

<div id="hv-chart-3"></div>

## Injuries & Death

Below, we summarized the crashes by the number of injuries and death in each incident. Note that during pandemic (2020), there are more crashes causing injuries and death:

<div id="hv-chart-4"></div>

<div id="hv-chart-5"></div>

# New York

This section examined the non-spatial changes of crash patterns in New York.

## Total Trend

Below, we show the monthly trend of total crash counts:

<div id="hv-chart-6"></div>

Note that due to the decrease of total traffic volume, the 2020 data may be incomparable with the 2019 data, so we adjusted the crash count in terms of the total traffic volume (using the Apple Map data):

<div id="hv-chart-7"></div>

## Month & Time

Below, we show the time pattern of crashes. Note that most crashes happened in the afternoons, and there are more crashes in summer months (June, July, August):

![New York 2020]({{ site.url }}{{ site.baseurl }}/assets/images/nyhourmonth2020.png)

There is no significant difference between the 2019 pattern and the 2020 pattern:

![New York 2019]({{ site.url }}{{ site.baseurl }}/assets/images/nyhourmonth2019.png)

## Reason

Below, we show the top 10 reasons of crashes. Note that during pandemic (2020), there are more crashes caused by Speeding, Disregarding traffic signals and Lack of experience:

<div id="hv-chart-8"></div>

## Injuries & Death

Below, we summarized the crashes by the number of injuries and death in each incident. Note that during pandemic (2020), there are more crashes causing injuries and death:

<div id="hv-chart-9"></div>

<div id="hv-chart-10"></div>
