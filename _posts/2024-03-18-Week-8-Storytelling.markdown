---
layout: page
title:  "San Franscio, how do they address the problem with vehicle thefts?"
date:   2024-03-18 11:46:00 +0100
categories: Data, Visualization, Storytelling
---

San Francisco, renowned for its Golden Gate Bridge, faced high crime rates in the 2000s, particularly auto theft. We analyzed the San Francisco Police Dataset (2003–2017) which contains records of reported incidents within the city, such as the crime type, location, date, and time. By analyzing this dataset, we aimed to find potential correlations in the evolution of vehicle theft data and the political and social situation of San Francisco.

Despite privacy concerns, 68 CCTV cameras were installed in the city since 2005. Studies, though varied, consistently show that CCTV impacts non-violent crimes. Based on this information, it is reasonable to suggest that the installation of CCTV in San Francisco contributed to decreasing vehicle thefts. This hypothesis is suggested by the time series chart which reflects a significant difference in the number of reported vehicle thefts after 2005.

![timeSeries](https://github.com/jesusdp-drcmr/jesusdp-drcmr.github.io/blob/main/assets/images/TimeSeries.png)
*Caption*

This heatmap shows the difference in vehicle thefts in each district in san francisco from the year 2005 to 2006. The more red the area the less vehicles were stolen in the district relative the 2005. Interestingly this shows perhaps the area of most focus, and where the police set up the most cameras to prevent vehicle theft. This also highly correlates with the position of the camera as can be seen on this link https://www.google.com/maps/d/viewer?mid=1gn9aYH09MHPQk7YD9EbOwg_sGJEFtefN&hl=en_US&ll=37.75638790588526%2C-122.3895447&z=13 (Select community camera)

![heatmap](https://github.com/jesusdp-drcmr/jesusdp-drcmr.github.io/blob/main/assets/images/heatmap.png)
*Caption*

Figure 3 depicts a multi-line graph illustrating the normalized incidence of vehicle thefts across various districts in San Francisco from 2003 to 2017. Upon analyzing the distribution of vehicle thefts over the years, it becomes evident that the Tenderloin district consistently emerges as the safest area with regards to vehicle theft. This observation may seem unexpected, considering the reputation of the Tenderloin district for its prevalence of crimes. However, its reputation stems from violent crimes. Conversely, Ingleside district generally exhibits the highest ratio of vehicle thefts, positioning it as one of the least secure areas in this regard.

<iframe src="https://github.com/jesusdp-drcmr/jesusdp-drcmr.github.io/blob/main/assets/images/MultiLineNorm.html" width="800" height="600"></iframe>



[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
