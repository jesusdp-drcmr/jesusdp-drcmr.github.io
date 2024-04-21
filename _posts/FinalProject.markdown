---
layout: page
title: "Exploring Mental Health"
date: 2024-04-21 16:40:00 +0100
categories: 
  - Data
  - Mental Health
---

The prevalence of common mental disorders is increasing among the populations of Western developed nations (1). Notably, Depressive Disorder (DD) stands out as one of the most significant mental health challenges. 

While mental illnesses are treatable, accurately estimating their prevalence and understanding their potential associations with other factors remains challenging. To address this, it is crucial to collect reliable data and analyze it effectively to comprehend these conditions—examining how, when, and why they occur, as well as the number of people affected by them.

With this project, we aim to study a series of datasets encompassing the prevalence of various mental health disorders globally and across different years, with a special focus on DD, and other related information. More specifically, we seek to study the relationship between DD with other factors, such as Alcohol or Drug disorders, or Suicide Rates, both globally and in greater detail within those countries where DD is a significant problem.

In order to gain a better understanding of the global situation of depression prevalence, we’ve developed an interactive bar chart plot that serves as a dynamic tool to explore and visualize the prevalence of depression annually from 1990 to 2017. Figure 1 allows users to select a specific year and highlights countries with both the highest and lowest depression prevalence. Notably, Greenland consistently stands out with the highest prevalence.  


&nbsp;

<iframe src="/assets/images/interactive_plot_1990_2017.html" width="630" height="405"></iframe>
*Figure 1: Depression Prevalence. *

&nbsp;


Figure 2 depicts a heatmap with data from the most recent year, 2017, illustrating the distribution of global depression prevalence. Greenland, with a prevalence of 6.55%, remains at the forefront. As can be seen in Figure 2, there is a contrast between developed and less-developed countries. 

&nbsp;

![heatmap](/assets/images/dd_heatmap.png)  
*Figure 2: Heatmap.*

&nbsp;

In 2017, while Greenland reported the highest prevalence, countries like Albania, Myanmar, Poland, Peru, and Romania displayed notably lower rates. We suggest that this divergence could stem from two potential reasons. First, depression might genuinely be less prevalent in these countries. Alternatively, due to the current state of these countries, limited resources and efforts might be put in when carrying out surveys and studies, thus, these lower rates may reflect the lack of interest or prioritization in mental health research in these countries. 

Since World War II, Greenland has undergone significant social and political transformations. This has caused profound changes within the Greenland society, impacting the population’s mental health in both positive and negative ways.
It is worth mentioning a study carried out in 2014 by the WHO, which highlighted gender-specific trends. In particular, this survey showed that girls in Greenland reported higher levels of depression, nervousness, and sleep difficulties compared to boys. This trend can be corroborated by our data, as seen in Figure 3.

![malevsfemale](/assets/images/malevsfemale.png)  
*Figure 3: *

Notably, the prevalence among females has consistently been approximately twice as high as among males. However, recent data suggest a promising trend of decreasing the prevalence, indicating potential improved interventions targeting the female population in Greenland. 
Another significant finding from the same survey points towards the heightened vulnerability of younger individuals, being identified as the most susceptible group, facing increased risks associated with depression, substance abuse, and suicidal tendencies. This affirmation is supported by Figure 4, which shows the prevalence of depression across different age groups in Greenland in 2017. As illustrated, the highest prevalence rate is associated with the population between 20-24 years old. 


![agegroups](/assets/images/agegreenland.png)  
*Figure 4: *

Exploring the Link Between Alcohol and Drug Disorders with Suicide Rates.

There is a prevailing hypothesis suggesting that high rates of substance consumption might contribute to elevated depression and suicide rates. With this in mind, we sought to investigate potential correlations between alcohol and drug disorders and depression prevalence and suicide rates. 


![drugalc](/assets/images/drugalc.png)  
*Figure 5: *

Figure 5 reveals striking trends in the prevalence of alcohol and drug disorders in Greenland against the average of different European countries across the last decades. Given these findings on the prevalence of alcohol and drug disorders, it is plausible to suggest a potential correlation between these elevated rates and depression and suicide in Greenland.



**References**

1. Hidaka, B. H. (2012). Depression as a disease of modernity: explanations for increasing prevalence. Journal of affective disorders, 140(3), 205-214.


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
