# MIUI Weather - A Fork

This is a fork of [MIUI Weather](https://www.deviantart.com/yahibazou/art/MIUI-Weather-295260009) Rainmeter skin by [YahibazOu](https://www.deviantart.com/yahibazou)

This is due to changes made to Weather.com and discontinuing public access to the XML API.
Took me a little over a day to workout how to scrape and pharse the site data into the skin.

## Improvements

The Original skin called out to the API about 3-4 times for different needs.
This is not needed, as a Single Web Parse is able to pull the data down, and a series of Child meaures can be used for pharse additional data.

Removed some older Bangs that had been deprecated in Rainmeter 4

## Setup

In order to use the skin you need to define the following Variables

WeatherLocation - You can find these codes from https://weather.codes/
ImperialMetric - "e" for Imperial (F) or "m" for Metric (C)
