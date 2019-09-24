---
layout: page
#
# Content
#

subheadline: "Data Science has been applied to analyze the impact on the environment of this measure."
title: "What does science really say about Madrid Central?"
teaser: "During ICSC-CITIES 2019 we will present our analysis of the environmental impact (air and noise pollution) of this measure. See here the main outcomes of this work."
categories:
  - publications
tags:
  - publication
  - smart cities
  - jamal

#
# Styling
#
header: no
image: 
    title: madrid-central-head.jpg
    thumb: madrid-central-dump.jpg
    homepage: brussels_header.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---

****

This post summarizes the main outcomes of our research work entitled **Assessing the environmental impact of car restrictions policies: Madrid Central case**. 


Authors:
- [**Irene Lebruán, Ph.D.**](https://www.researchgate.net/profile/Irene_Lebrusan_Murillo) in Sociology and RCC Postdoctoral Researcher at Harvard University.
- [**Jamal Toutouh, Ph.D.**](https://www.jamal.es) in Computer Science and Marie-Curie Postdoctoral Fellow at Massachusetts Institute of Technology.
 

---

#### Motivation

Air pollution is the top health hazard in the European Union, as it reduces life expectancy, loss of years of healthy life, and diminishes the quality of health. 
Noise pollution is also a major environmental concern that critically impacts the quality of life of the city inhabitants. 
Accordingly, and under the risk of fines, countries are required to reduce noise and air pollutants.

Focusing on air pollution, European Union demanded to Spain the reduction of this type of pollutants (mainly nitrogen dioxide, NO2),
under the thread of the risk of important economic sanctions. 
This process is paralyzed in May 2018 thanks to the adoption of measures to reduce pollutants, such as Madrid Central.

However, this measure has been controversial, as different social and political groups consider it to be bothersome and ineffective. Thus, the elections (held on May, 26th 2019) the new government to apply a moratorium to override the measure (by not fining drivers who do not comply with the specific traffic regulations in Madrid Central).

We ([*Irene Lebruán, Ph.D.*](https://www.researchgate.net/profile/Irene_Lebrusan_Murillo) postdoctoral researcher at Harvard and me) decided to apply Data Science to analyse the real data gathered by the air quality and noise sensor installed in Madrid Central and shared though the [Madrid Open Data Portal](https://datos.madrid.es). The temporal range of this study starts in December of 2016 and finishes in may of 2019, i.e., 30 moths groped in two periods: 24 months previous Madrid Central (Pre-MC) and six months with the car restrictions (Post-MC). The complete work, entitled [*Assessing the environmental impact of car restrictions policies: Madrid Central case*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf), and results will presented during the [*I Ibero-American Congress of Smart Cities (ICSC-CITIES 2019)*](http://icsc-cities2019.com/EN_index.html).  



#### Results    
In this post, we present the results in terms of NO2 because is the pollutant that almost lead Spain to European Court. However, in our [*paper*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf) we evaluate more air pollutants.

The following table reports the minimum (min), mean, and maximum (max) values of the concentration of NO2 in the air sensed during the evaluated periods in terms of micro-grams per cubic meter. 
  
|   | Pre-MC | | - | | Post-MC | | 
| min        | mean           | max  | - | min        | mean           | max  |
| ----:|---------:| -----:|:---------:|-------------:|-------:| -----:|
| 15.00     | 46.92 | 96.00 | - | 8.00 | 39.60 | 96.00 |

The following figure shows the mean and standard deviation of the concentration of NO2 grouped by months. 
When we compare the same months with the car restrictions or without them (e.g., May of 2019 vs May of 2018 and 2017) we observe that the NO2 concentration is significantly reduced in more than one third (35.65% of reduction).   

![NO2 mean and standard deviation](https://jamaltoutouh.github.io/images/blog/air_NO2.png "Mean and standard deviation")  

Finally, we carried out a temporal analysis of the data. The next figure shows the NO2 concentration during the 30 months evaluated in this research. According to the regressions computed (black lines in the figure), there is a declined trend over time on the concentration of NO2 in the air. That is, Madrid Central has caused the NO2 concentration to decrease over time.   

![NO2 regression](https://jamaltoutouh.github.io/images/blog/air_NO2_regression.png "NO2 regression")  

 
The lowering of NO2 is a very positive result. This is the component of pollution that affects health the most, increasing bronchitis asthma and lung problems especially among the children and the older people. Besides, this is the component that lowering was specifically required to Spain by the EU. Accordingly, the reduction of this pollutant is extremely positive, not just having a positive effect on health but fulfilling so the international directions and so, avoiding the risk of fine. 

A similar positive impact on noise pollution is shown when we apply Data Science to evaluate the data. [*Our paper*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf) further illustrates the analysis and results. 
  
 

The main draft of our paper can be downloaded from [*here*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf)

---

### Assessing the environmental impact of car restrictions policies: Madrid Central case
#### Abstract
With the increase of population living in urban areas, many transportation-related problems have grown very rapidly. Pollution causes many inhabitants health problems. A  major concern for the International Community is pollution, which causes many inhabitants health problems. Accordingly, and under the risk of fines, countries are required to reduce noise and air pollutants. As a way to do so, road restrictions policies are applied in urban areas. Evaluating objectively the benefits of this type of measures is important to asses their real impact. In this work, we analyze the application of Madrid Central (MC), which is a set of road traffic limitation measures applied in the downtown of Madrid (Spain), by using smart city tools. According to our results, MC significantly reduces the nitrogen dioxide (NO2) concentration in the air and the levels of noise in Madrid, while not arising any border effect.




 
