---
title: "Hurricane Ida Twitter Activity"
date: 2023-12-18
categories:
  - Reproduction
tags:
  - GIS
  - Science
  - Reproduction
---

This study is a replication of Professor Holler's study of Twitter activity during Hurricane Dorian in 2019, instead analyzing Twitter activity during Hurricane Ida in 2021. To assess Twitter activity, the study uses tweets with keywords related to the hurricane during this time period in the eastern United States.
Tweets are analyzed for temporal distribution, networks, text content, and spatial distribution.
Holler (2019) developed a Normalized Difference Tweet Index (NDTI) to measure relative abundance of tweets about a hurricane event in each county, normalizing by the number of non-hurricane tweets in each county.

Due to changes in Twitter's API availability that prevented new Twitter data from being collected for this study, this replication study uses county population to calculate the tweet rate for NDTI.
To determine hotspots of Twitter activity, the study uses the Getis Ord G\* method.
Additional deviations I made from Holler (2019) include visualizing the geographic area of the search queries, using all counties that fall within the search area, and improving visualizations of analyses.

[Hurricane Ida replication study report](https://eliseylchan.github.io/RPl-Ida/)

[Github repository](https://github.com/eliseylchan/RPl-Ida)

References:

> Holler, Joseph (2019). Hurricane Dorian vs Sharpie Pen: an empirical test of social amplification of risk on social media. <https://www.github.com/gis4dev/OR-Dorian>
