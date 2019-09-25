---
layout: page
#
# Content
#

subheadline: "Smart City tools and Data Science have been applied to analyze the effects of Madrid Central, an environmental measure enforced in Spain."
title: "What does science really say about Madrid Central?"
teaser: "During ICSC-CITIES 2019 we will present our analysis of the environmental impact (air and noise pollution) of this measure. You can consult here the complete outcomes of this work."
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

Briefly, this post highlights the main outcomes of our research work entitled **Assessing the environmental impact of car restrictions policies: Madrid Central case**. 


Authors:
- [**Irene Lebrusán, Ph.D.**](https://www.researchgate.net/profile/Irene_Lebrusan_Murillo) in Sociology and RCC Postdoctoral Researcher at **Harvard University**.
- [**Jamal Toutouh, Ph.D.**](https://www.jamal.es) in Computer Science and Marie-Curie Postdoctoral Fellow at **Massachusetts Institute of Technology**.
 

---

#### Motivation

Air pollution is the top health hazard in the European Union (EU): it reduces life expectancy, provokes loss of years of a healthy life, and diminishes the quality of life. Noise pollution is also a major environmental concern, as it critically impacts the quality of life of the city inhabitants. Accordingly, and under the risk of fines, Member States of the EU are required to reduce noise and air pollutants.
The European Union specifically demanded to Spain, under the risk of important economic sanctions, to reduce air pollutants (mainly nitrogen dioxide, NO2). Thanks to measures like Madrid Central, focused on the traffic reduction, Spain managed to stop the disciplinary action in May 2018. 
However, this measure has been controversial, as different social and political groups consider it to be bothersome and ineffective. In fact, and after the elections (held on May, 26th 2019) the new government reversed the driving ban stated by Madrid Central, applying a moratorium to override the measure. The question here is: Was Madrid Central an effective measure to reduce air pollutants and noise? 

We ([*Irene Lebrusán, Ph.D.*](https://www.researchgate.net/profile/Irene_Lebrusan_Murillo), a postdoctoral researcher at Harvard and Jamal Toutouh, Ph.D., postdoctoral researcher at MIT) decided to apply Data Science to analyse the impact of Madrid Central over air quality and noise. We analyzed data gathered by the sensors installed in Madrid Central and shared though the  [Madrid Open Data Portal](https://datos.madrid.es). The temporal range of this study starts in December of 2016 and finishes in may of 2019, i.e., 30 moths groped in two periods: 24 months previous Madrid Central (Pre-MC) and six months with the car restrictions (Post-MC). The complete work, entitled [*Assessing the environmental impact of car restrictions policies: Madrid Central case*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf), and results will presented during the [*II Ibero-American Congress of Smart Cities (ICSC-CITIES 2019)*](http://icsc-cities2019.com/EN_index.html).  



#### Results    
This post highlights the results in terms of NO2, as this is the pollutant that almost leads Spain to the European Court.  If you are interested in the results of other air pollutants, you can check it in our [*paper*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf).

The following table reports the minimum (min), mean, and maximum (max) values of the concentration of NO2 in the air sensed during the evaluated periods in terms of micro-grams per cubic meter. 
  
|   | Pre-MC | | - | | Post-MC | | 
| min        | mean           | max  | - | min        | mean           | max  |
| ----:|---------:| -----:|:---------:|-------------:|-------:| -----:|
| 15.00     | 46.92 | 96.00 | - | 8.00 | 39.60 | 96.00 |

The following figure shows the mean and standard deviation of the concentration of NO2 grouped by months. When we compare the same months with the car restrictions or without them (e.g., May of 2019 vs May of 2018 and 2017) we observe that the NO2 concentration is significantly reduced in more than one third (35.65% of reduction).
![NO2 mean and standard deviation](https://jamaltoutouh.github.io/images/blog/air_NO2.png "Mean and standard deviation")  

Finally, we carried out a temporal analysis of the data. The next figure shows the NO2 concentration during the 30 months evaluated in this research. According to the regressions computed (black lines in the figure), there is a declined trend over time on the air concentration of NO2. That is, Madrid Central has caused the NO2 concentration to decrease over time.
![NO2 regression](https://jamaltoutouh.github.io/images/blog/air_NO2_regression.png "NO2 regression")  
 
The lowering of NO2 is a very positive result. This is the component of pollution that affects health the most, increasing bronchitis asthma and lung problems, especially among the children and the older people. Besides, this is the component on which the lowering was specifically required to Spain by the European Commission. Accordingly, the reduction of this pollutant is extremely positive, not just having a positive effect on health but fulfilling so the international directions and so, avoiding the risk of fine. 

A similar positive impact on noise pollution is shown when we apply Data Science to evaluate the data. [*Our paper*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf) further illustrates the analysis and results. 
  
The main draft of our paper can be downloaded from [*here*](https://jamaltoutouh.github.io/downloads/lebrusan2019.pdf)

---

### Assessing the environmental impact of car restrictions policies: Madrid Central case
#### Abstract

With the increase of population living in urban areas, many transportation-related problems have grown very rapidly. Pollution causes many inhabitants health problems. A  major concern for the International Community is pollution, which causes many inhabitants health problems. Accordingly, and under the risk of fines, countries are required to reduce noise and air pollutants. As a way to do so, road restrictions policies are applied in urban areas. Evaluating objectively the benefits of this type of measures is important to asses their real impact. In this work, we analyze the application of Madrid Central (MC), which is a set of road traffic limitation measures applied in the downtown of Madrid (Spain), by using smart city tools. According to our results, MC significantly reduces the nitrogen dioxide (NO2) concentration in the air and the levels of noise in Madrid, while not arising any border effect.



 
