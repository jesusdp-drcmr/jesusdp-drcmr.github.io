---
layout: page
title: "San Francisco: Addressing Vehicle Theft Problems"
date: 2024-03-23 16:40:00 +0100
categories: 
  - Data
  - Visualization
  - Storytelling
---

San Francisco, renowned for its Golden Gate Bridge, faced high crime rates in the 2000s, particularly auto theft. We analyzed the San Francisco Police Dataset (2003–2017), which contains records of reported incidents within the city, such as the crime type, location, date, and time. By analyzing this dataset, we aimed to find potential correlations in the evolution of vehicle theft data and the political and social situation of San Francisco.

Despite privacy concerns, 68 CCTV cameras were installed in the city since 2005 [1]. However, based on the data, we suggest that the installation of CCTV actually had an impact on the number of vehicle thefts, reducing them. Our reasoning is that although the system doesn't actively contribute to reducing crime, it may have an impact on non-violent crimes. This hypothesis is suggested by Figure 1, which reflects a significant difference in the number of reported vehicle thefts after 2005 when CCTV was initially installed in San Francisco. The number of reported vehicle thefts continued to decrease until 2010, subsequently increasing but not matching the levels observed before the introduction of CCTV.


Figure 2 illustrates the variation in vehicle thefts across different districts in San Francisco from 2005 to 2006. The intensity of red shading corresponds to the relative decrease in stolen vehicles within each district compared to 2005. Overall, there was a significant disparity in vehicle theft, ranging from -64% to -56% compared to the previous year. Interestingly, this pattern aligns with the areas of highest police focus, where additional surveillance cameras were strategically placed to prevent vehicle theft in the Tenderloin, Park, and Taraval districts. Notably, these camera positions correlate closely with the observed changes in theft rates


![timeSeries](/assets/images/TimeSeries_v2.png)  
*Figure 1: Line graph representing the number of vehicle thefts in San Francisco, before and after the installation of the CCTV system.*

&nbsp;

![heatmap](/assets/images/heatmap_v2.png)  
*Figure 2: Heatmap showing Vehicle Theft difference from 2005 to 2006 by Police District in San Francisco.*

&nbsp;

<iframe src="/assets/images/MultiLineNorm.html" width="630" height="405"></iframe>
*Figure 3: Multi-line interactive graph illustrating the normalized incidence of vehicle thefts across various districts in San Francisco from 2003 to 2017*

&nbsp;


According to Figure 3, the Tenderloin district consistently emerges as the safest area with regards to vehicle theft, which as discussed before, showed the biggest reduction in reported auto thefts after the CCTV installation in 2005. This observation may seem unexpected, considering the reputation of the Tenderloin district among others in the center such as Mission, for its prevalence of crimes, which may be mainly by violent crimes. On the other hand, the Ingleside district generally exhibits the highest ratio of vehicle thefts, positioning it as one of the least secure areas in this regard, probably due to its proximity to access points to major highways. However, it is important to point out that, following a rise in vehicle thefts starting in 2011, Ingleside reached its peak in 2014 before declining gradually.

It is indeed noteworthy that the number of vehicle thefts peaked in 2015 across several districts, including Mission and Northern. We propose that this surge may be linked to justice reforms. Specifically, in November 2014, Proposition 47 was introduced, which downgraded certain nonviolent felonies to misdemeanors [3]. However, this change sparked controversy, and definitive conclusions regarding the impact of justice reforms on crime rates remain elusive.

In conclusion, our analysis of the San Francisco Police Dataset revealed intriguing insights into the impact of CCTV installation on vehicle theft rates in the city. Despite initial concerns and opposition, manifesting the inefficacy of this system, the beginning of the installation of CCTV cameras coincided with a noticeable reduction in reported vehicle thefts, suggesting a potential deterrent effect on non-violent crimes such as these. Our analysis, based on geolocated data, suggests that the installation of the CCTV had a big impact from 2005 to 2006 in districts such as Tenderloin or Park, which are known for having a high affluence of vehicles, and thus, targets for this type of crimes.

Furthermore, the multi-line interactive graph in Figure 3 illustrates how the introduction of CCTV contributed to reduce the number of vehicle thefts across different districts over time. Tenderloin district exhibits the most significant decline in thefts post-CCTV installation. However, challenges remain, as evidenced by fluctuations in theft rates observed post-2010 and the persistent high incidence in districts like Ingleside. This underscores the need for continued evaluation and adaptation of surveillance strategies alongside complementary crime prevention measures to ensure sustained improvements in public safety throughout San Francisco.

**References**

[1] Knight, Heather (2008, March 21). “Crime cameras not capturing many crimes” San Francisco Chronicle.

[2] Google Maps. (23/03/2024). Community Cameras in San Francisco. Retrieved from [https://www.google.com/maps/d/viewer?mid=1gn9aYH09MHPQk7YD9EbOwg_sGJEFtefN&hl=en_US&ll=37.75638790588526%2C-122.3895447&z=13](https://www.google.com/maps/d/viewer?mid=1gn9aYH09MHPQk7YD9EbOwg_sGJEFtefN&hl=en_US&ll=37.75638790588526%2C-122.3895447&z=13)

[3] Ho, Vivian & Veklerov, Kimberly (2016, March 16). "SF car break-ins up 31 percent, nearly triple in 5 years" San Francisco Chronicle. 

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
