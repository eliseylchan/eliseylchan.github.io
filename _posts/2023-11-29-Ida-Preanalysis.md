---
title: "Preanalysis of Hurricane Ida Twitter Replication"
date: 2023-11-29
categories:
  - Blog
tags:
  - GIS
  - Science
  - Replication
---

For my independent project, I am analyzing Twitter activity during Hurricane Ida. The hurricane made landfall in Louisiana and made its way up the east coast of the US in September 2021. This study is a replication of Professor Holler's study analyzing Twitter activity during Hurricane Dorian in response to the [Sharpiegate controversy](https://en.wikipedia.org/wiki/Hurricane_Dorian%E2%80%93Alabama_controversy). 

Geographic threats to validity (Schmitt 1978) in the Hurricane Dorian study remain in the Hurricane Ida study. The study uses Getis Ord Gi* analysis to identify hotspots of Twitter activity during the hurricane event. This method is susceptible to boundary effects because the region of the analysis, in this case the radius of the Twitter search, will change the results by changing the mean value of Twitter activity. 

The spatial component of the Twitter data isn't very precise. Few tweets have exact coordinates, so most of the tweets in this study rely on the neighborhood or city bounding box. This study could be susceptible to scale distortions, however using counties as the analysis region rectifies this threat to validity because all parts of cities and neighborhoods should fall within the same county.

One difference between the Hurricane Dorian and Hurricane Ida studies is the availability of Twitter data. In the Dorian study, generic tweets (those without Hurricane Dorian content) were used to find the hurricane event tweet rate and the Normalized Tweet Difference Index (NDTI). Making a search for generic tweets wasn't possible (for free) at the time of the Ida study, so instead I use Census population data. While not a specifically geographic threat to validity, this data loss opens up uncertainty about how to estimate the number of tweets. 


References:

> Schmitt, R. R. (1978). Threats to validity involving geographic space. Socio-Economic Planning Sciences, 12(4), 191–195. https://doi.org/10.1016/0038-0121(78)90044-7
