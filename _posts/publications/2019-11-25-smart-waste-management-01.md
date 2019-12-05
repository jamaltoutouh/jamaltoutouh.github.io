---
layout: page
#
# Content
#

subheadline: "Artificial Intelligence helps us to find the best location of the garbage collection points in the city. "
title: "Where to Locate the Garbage Collection Points (Bins)?"
teaser: "We are researching about optimization problem of locating and configuring the garbage collection points. The main idea is to provide the best service to the city inhabitants while minimizing the costs. Some results have been already published."
categories:
  - publications
tags:
  - publication
  - smart cities
  - jamal
  - smart waste management

#
# Styling
#
header: no
image: 
    title: smart_waste_management_head.jpg
    thumb: smart-waste-management_LOGO.jpg
    homepage: brussels_header.jpg
#    caption: Photo by Corey Blaz
#    caption_url: https://blaz.photography/
mediaplayer: false
---

****


Enhancing efficiency in Municipal Solid Waste Management (MSWM) Systems is crucial for local governments and inhabitants. This post presents two research works published in different journals addressing MSWM. This research has been carried out in collaboration with two other researchers:

- [**Sergio Nesmachnow, Ph.D.**](https://www.fing.edu.uy/inco/grupos/cecal/hpc/pmwiki/pmwiki.php?n=Main.SergioNesmachnow)  Full Professor in the Numerical Center (CeCal) at Computer Science Institute, Engineering Faculty **Universidad de la Republica** (Uruguay).
- [**Diego Gabriel Rossit, Ph.D.**](https://www.conicet.gov.ar/new_scp/detalle.php?keywords=&id=44156&datos_academicos=yes) Researcher at the Department of Engineering at Universidad Nacional del Sur and at **CONICET** (Argentina).

The main goal of this research is to provide an efficient waste collection infrastructure that maximizes the quality of the service provided to the citizens, but taking into account the costs. These costs includes both the economical costs and  the required number of visits of the collection vehicles. These studies have been applied in real regions of Uruguay and Argentina. 
During *LION 12* (2018) we presented a preliminary approach [**(see the slides)**](https://jamaltoutouh.github.io/downloads/Toutouh_LION2018.pdf). 


![Illustration of the problem representation](https://github.com/jamaltoutouh/jamaltoutouh.github.io/blob/master/images/blog/waste-management-representation.jpg?raw=true "Illustration of the problem representation")  


In order to address this MSWM problem, we have proposed different methods based on *Linear Programming*, different *heuristics* (such as PageRank), and *Evolutionary Algorithms*. 

We have already published the results in the following journals:


0. J. Toutouh, D. G. Rossit, and S. Nesmachnow (2019). **Soft computing methods for multiobjective location of garbage accumulation points in smart cities**. *Annals of Mathematics and Artificial Intelligence* *(In Pres)* [doi: 10.1007/s10472-019-09647-5](https://link.springer.com/article/10.1007/s10472-019-09647-5).

0. D. G. Rossit, S. Nesmachnow, and J. Toutouh (2019). **A bi-objective integer programming model for locating garbage accumulation points: a case study**. *Revista de Ingeniería* *(In Pres)* [doi: 10.17533/udea.redin.20190509](https://doi.org/10.17533/udea.redin.20190509). 

And the following conference:

0. J. Toutouh, D. Rossit, S. Nesmachnow (2018). **Computational intelligence for locating garbage accumulation points in urban scenarios**. *International Conference on Learning and Intelligent Optimization, LION 12*, pp. 1-15, 2018. *Lecture Notes in Computer Science, vol 11353.* [doi: 10.1007/978-3-030-05348-2_34](https://doi.org/10.1007/978-3-030-05348-2_34).


See the abstracts bellow:

### Soft computing methods for multiobjective location of garbage accumulation points in smart cities
This article describes the application of soft computing methods for solving the problem of locating garbage accumulation points in urban scenarios. This is a relevant problem in modern smart cities, in order to reduce negative environmental and social impacts in the waste management process, and also to optimize the available budget from the city administration to install waste bins. A specific problem model is presented, which accounts for reducing the investment costs, enhance the number of citizens served by the installed bins, and the accessibility to the system. A family of single- and multi-objective heuristics based on the PageRank method and two mutiobjective evolutionary algorithms are proposed. Experimental evaluation performed on real scenarios on the cities of Montevideo (Uruguay) and Bahía Blanca (Argentina) demonstrates the effectiveness of the proposed approaches. The methods allow computing plannings with different trade-off between the problem objectives. The computed results improve over the current planning in Montevideo and provide a reasonable budget cost and quality of service for Bahía Blanca.

### A bi-objective integer programming model for locating garbage accumulation points: a case study
Enhancing efficiency in Municipal Solid Waste (MSW) management is crucial for local governments, which are generally in charge of collection, since this activity explains a large proportion of their budgetary expenses. The incorporation of decision support tools can contribute to improve the MSW system, specially by reducing the required investment of funds. This article proposes a mathematical formulation, based on integer programming, to determine the location of garbage accumulation points while minimizing the expenses of the system, i.e., the installment cost of bins and the required number of visits the collection vehicle which is related with the routing cost of the collection. The model was tested in some scenarios of an important Argentinian city that stills has a door-to-door system, including instances with unsorted waste, which is the current situation of the city, and also instances with source classified waste. Although the scenarios with classified waste evidenced to be more challenging for the proposed resolution approach, a set of solutions was provided in all scenarios. These solutions can be used as a starting point for migrating from the current door-to-door system to a community bins system.

### Computational Intelligence for Locating Garbage Accumulation Points in Urban Scenarios
This article presents computational intelligence methods for solving the problem of locating garbage accumulation points in urban scenarios, which is a relevant problem in nowadays smart cities to optimize budget and reduce negative environmental and social impacts. The problem model considers reducing the investment costs, enhance the proportion of citizens served by bins, and the accessibility to the system. A family of heuristics based on the generic PageRank schema and a mutiobjective evolutionary algorithm are proposed. Experimental evaluation performed on real scenarios on the city of Montevideo, Uruguay, demonstrates the effectiveness of the proposed approaches. The methods allow computing plannings with different trade-off between the problem objectives and improving over the current planning.
