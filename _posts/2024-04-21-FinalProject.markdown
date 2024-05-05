---
layout: default
title: "Exploring Mental Health"
date: 2024-04-21 16:40:00 +0100
categories: 
  - Data
  - Mental Health
---

<div style="text-align: justify;">

Mental illnesses are becoming increasingly common worldwide. Depression is among the most prevalent mental health disorders impacting adults globally, and its rising rates across the general population have elevated it to a serious public health issue (1). One of the countries that suffers from a high depression rate is Greenland. <br><br>

Greenland has undergone significant social and political transformations since World War II, resulting in considerable changes in its society. These transformations have influenced the mental health of its population, with depression becoming a major concern. <br><br>

In Greenland, the healthcare system is challenged by a lack of qualified healthcare providers, financial constraints, and having to deliver high-quality treatments in a very large and sparsely populated country. Thus, accurately estimating the prevalence of depression and understanding its potential relations with other factors remains challenging. <br><br>
 
How does Greenland's situation compare to other countries? What factors might explain these differences? How is depression distributed across the population, and are there any clear trends or patterns that reveal the unique challenges and dynamics of depression prevalence in Greenland? To explore these questions, we will use data visualisation techniques. <br><br>

To set the stage for our analysis of Greenland's data, we begin by providing a snapshot of the global landscape of depression prevalence through a choropleth map (Figure 1). It allows for an examination of the annual prevalence of depression worldwide from 1990 to 2017, highlighting countries with both the highest and lowest rates of depression. However, it is worth noting that depression cases may be underreported in many countries due to social stigma or due to limited resources and effects put in when carrying out surveys and studies. <br><br>


<div style="text-align: center;">
<iframe src="/assets/images/depression_world_map.html" width="1000" height="520"></iframe>
</div>

<div style="text-align: center; font-style: italic;">
Figure 1: Interactive World Heatmap of Depression Prevalence from 1990 to 2017.
</div><br><br>

As can be unfolded, Greenland consistently stands out with the highest depression prevalence rates. Illustrated in Figure 2, although there are fluctuations and a general downward trend in depression rate in Greenland, it is still considerably higher than the global average prevalence. From 2014 to 2017, where it can be seen a decreasing pattern in depression prevalence, the Greenlandic government implemented various initiatives to address mental health issues. For example, the Ministry of Education, Culture, Research, and Church included provisions in their plan to offer psychological therapy for students (2). Additionally, since 2010, the Ministry of Health of Greenland has implemented a national intervention called "Early Intervention," which aims to reduce the risk of children developing behavioral, mental, or physical health problems, or encountering difficulties in school (2). <br><br>

<div style="text-align: center;">
<img src="/assets/images/greevsworld.png" alt="Time Series Graph of Depression Prevalence in Greenland (Red) and the Global Average (Gray)." width="600">
</div>

<div style="text-align: center; font-style: italic;">
Figure 2: Time Series Graph of Depression Prevalence in Greenland (Red) and the Global Average (Gray).
</div><br><br>

Before exploring the data from Greenland, let's examine how depressive disorder is related to other disorders. Figure 3 presents a correlation heatmap, which shows correlations of each disorder with others. As can be seen, depression is positively correlated with anxiety disorders and drug use disorders, with correlation values of 0.38 and 0.37, respectively. These notable correlations warrant further investigation. Additionally, it would be useful to understand Greenland's position in comparison to Europe and world averages for various disorders.<br><br>

<div style="text-align: center;">
<iframe src="/assets/images/correlation_heatmap_general.html" width="600" height="600"></iframe>
</div>

<div style="text-align: center; font-style: italic;">
Figure 3: Interactive Heatmap showing the Correlation of Global Depression Prevalence with other Mental Disorders.
</div><br><br>

Compared to the average rates observed in Europe and worldwide over the last decades, striking trends in the prevalence of different disorders in Greenland can be seen in Figure 4. Greenland consistently exhibits higher rates in various disorders. In particular, prevalence of alcohol and drug use disorders in Greenland is twice the average of the European countries. According to authorities, risky use of alcohol and marihuana are one of the most important public health challenges in Greenland (3). Also, previous studies suggest that, in Greenland, the major alcohol-related problem was that a large proportion of the population indulged in repeated acute alcohol intoxication and not as in Denmark chronic alcoholism (4).  

<br><br>
<div style="text-align: center;">
<img src="/assets/images/trends_disorders_comparisom.png" alt="Time series graph showing the changes in Alcohol Use, Anxiety, and Drug Use disorders prevalence in Greenland against the European average and global average from 1990 to 2017." width="700" height="300">
</div>

<div style="text-align: center; font-style: italic;">
Figure 4: Time series graph showing the changes in Alcohol Use, Anxiety, and Drug Use disorders prevalence in Greenland against the European average and global average from 1990 to 2017.
</div><br><br>


Based on this, now we focus on the data of Greenland in particular, since identifying high-risk groups is essential for creating targeted public health interventions. Can there be variations in the prevalence of depressive disorders among different groups within the Greenlandic population? A 2014 study by the World Health Organization (WHO) underscored gender-specific trends in Greenland, noting that women reported higher levels of depression, nervousness, and sleep difficulties than men (5). As depicted in Figure 5, the prevalence of depression among females has consistently been approximately twice as high as among males. However, recent data indicates a promising trend of decreasing the prevalence, suggesting potential improvements in interventions targeting the female population.

<br><br>

<div style="text-align: center;">
<img src="/assets/images/malevsfe.png" alt="Time Series Graph showing the changes in Depression Prevalence in Greenland over time for males and females." width="600">
</div>

<div style="text-align: center; font-style: italic;">
Figure 5: Time Series Graph showing the changes in Depression Prevalence in Greenland over time for males and females.
</div><br><br>

When investigating the causes, a multivariate analysis of Greenlanders aged 18–59 identified significant predictors of depressive symptoms: unemployment among men and, for women, experiences of sexual abuse (6). Additionally, studies have suggested that the prevalence of childhood sexual abuse in Greenlandic females might be among the highest in the world (7). The impact of sexual abuse on the social and emotional well-being of children, as well as their development, is increasingly well understood. Furthermore, there is a documented link between the trauma of childhood sexual abuse and higher rates of various psychological and social challenges in adulthood, including depression. <br><br>

In general, older individual groups are the ones who are more vulnerable to suffer from depression. However, as demonstrated in Figure 6, the population aged 20-24 consistently shows the highest prevalence rate, confirming the persistent nature of the heightened vulnerability of younger individuals in Greenland. <br><br>

<div style="text-align: center;">
<iframe src="/assets/images/depression_prevalence_by_age.html" width="700" height="500"></iframe>
</div>

<div style="text-align: center; font-style: italic;">
Figure 6: Interactive Bar Chart showing the distribution of Depression Prevalence over different age groups in Greenland over the years.
</div><br><br>

We have observed worldwide correlations among disorders and noted that in Greenland, alcohol use disorders, drug use disorders, and anxiety disorders significantly exceed the averages in Europe and globally. Given these observed patterns, it becomes increasingly plausible to suggest a potential correlation between these elevated rates of alcohol and drug disorders and the rates of depression, and maybe suicide in Greenland. How do these disorders correlate within Greenland itself? Could there be underlying connections between them? <br><br>

Surprisingly, in Figure 7, we observe that the correlation patterns of disorders in Greenland diverge significantly from global trends. In Greenland, we see a decrease in depression rates over time, while both anxiety and drug use are on the rise. This discrepancy might suggest that while there is a significant focus on the high rates of depression, other disorders may have been neglected. Moreover, while no correlation between alcohol use and depression is observed globally, in Greenland specifically, both are seen to follow a declining trend over time. <br><br>

<div style="text-align: center;">
<iframe src="/assets/images/depression_correlation_green.html" width="800" height="500"></iframe>
</div>

<div style="text-align: center; font-style: italic;">
Figure 7: Interactive scatter plots of the Prevalence of Depression against Alcohol Use, Anxiety, and Drug Use Disorders in Greenland (1990-2017).
</div><br><br>

In conclusion, with this project we studied the complex landscape of depression and mental health in Greenland during the past decades, revealing and highlighting intriguing trends and correlations that can be used to predict future patterns. Notably, women consistently report higher levels of depression, while younger age groups, particularly those aged 20-24, appear most vulnerable. Furthermore, the correlation between depression and other disorders diverges from global patterns, suggesting unique dynamics within Greenland's population. <br><br>

Understanding these nuances is crucial for devising targeted interventions that address the multifaceted nature of mental health challenges in Greenland. Moving forward, holistic approaches that consider social, cultural, and economic factors alongside individual experiences are essential for fostering resilience and improving mental well-being in Greenlandic communities. <br><br>

As we continue to delve deeper into the data and collaborate across disciplines, we can hope to pave the way for more effective policies and support systems that promote mental health and resilience for all residents of Greenland. Through ongoing research and data-driven insights, we can strive towards a future where mental health disparities are addressed, and every individual has access to the care and support they need to thrive. <br><br>


**References**
<br><br>
1. Hidaka, B. H. (2012). Depression as a disease of modernity: explanations for increasing prevalence. Journal of affective disorders, 140(3), 205-214. <br><br>

2. Karsberg, S. (2016). Mental health among youth in Greenland: Who is responsible? What is being done?.<br><br>

3. Bjerregaard, P., Larsen, C. V., Sørensen, I. K., & Tolstrup, J. S. (2020). Alcohol in Greenland 1950-2018: consumption, drinking patterns, and consequences. International journal of circumpolar health, 79(1), 1814550.<br><br>

4. Clemmesen, C. (1958). Oversigt over alkoholproblemet på Grønland [Overview of the alcohol problem in Greenland. In Danish]. Ugeskr Læger, 120, 1374–1379.<br><br>

5. <br><br>

6. Bjerregaard, P., & Curtis, T. (2002). Cultural change and mental health in Greenland: the association of childhood conditions, language, and urbanization with mental health and suicidal thoughts among the Inuit of Greenland. Social Science & Medicine, 54(1), 33-48.<br><br>

7. Baviskar, S., & Christensen, E. (2011). Childhood sexual abuse of women in Greenland and its developmental correlates among their children. International Journal of Circumpolar Health, 70(1), 29-36.<br><br>


[jekyll-docs]: https://jekyllrb.com/docs/home <br><br>
[jekyll-gh]:   https://github.com/jekyll/jekyll <br><br>
[jekyll-talk]: https://talk.jekyllrb.com/ <br><br>
