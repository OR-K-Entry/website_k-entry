---
title: Data Sources & Variables for OR-K-Entry
author: Rebecca
date: '2020-05-22'
slug: data_post_1
categories: []
tags: [data, milestone]
subtitle: 'Welcome to Our First Blog Post!'
summary: ''
authors: [rebecca]
lastmod: '2020-05-22T12:42:28-06:00'
featured: yes
---

### An Introduction
OR-K-Entry, the research project shared on this site, is designed to address the racial/ethnic and socio-economic disparities in school readiness for incoming kindergarten students, of which there are many[^1]. The investigative team (learn more in the [people](../../authors) section) is leveraging various large-scale datasets collected on preschool children and their families to develop models that can guide intervention efforts and enhance children’s readiness to learn. The goal? Development of an innovative risk model that pools child, school, and community variables to clarify and strengthen intervention priorities.


![Creative commons photo of four preschool children sitting on the floor; one boy looks at the camera; one girl and one boy look at beetle and insect posters on the floor in front of the group; one girl looks off camera, apparently at a teacher](/img/creative_commons_ODA_kids_classroom_48632261198_4a99f7439d_b.jpg)


## What We're Doing Now
This project is early in the seed grant period. Our three objectives during this phase are to 

  1.	Develop a new data archive that pools economic and health-related outcomes with data on children’s readiness for kindergarten.  
  
  2.	Develop an initial “risk profile” model, forecasting the kindergarten readiness of children within specific communities, including evaluating the relative importance of different variables in the prediction algorithm. 
  
  3.	Assemble an initial data system and preliminary models that will be expanded in an R01 application to NICHD.


We're focused primarily on the child and community level data at this point.

## School & Child Level Data
School data and student data are provided by the Oregon Department of Education (ODE) with whom the project team has a long-standing relationship of collaboration, as well as existing data sharing agreements. We use data on the school facilities, staff demographics and student body demographic makeup in addition to data from the Oregon Kindergarten Assessment (OKA). 


The OKA measures children’s school readiness through the assessment of pre-academic (emergent literacy and mathematics) and classroom behavior regulation competencies crucial for successful transitions to kindergarten.[^2] OKA data were obtained for every student in the state from the 2013/14 school year, when the assessment was first administered to all incoming kindergarten students, through the current 2019-2020 school year.


We have collected basic student demographic data including

   * economic disadvantage status - defined by eligibility for free or reduced-price lunch.
   * gender
   * race / ethnicity
   * home addresses at the time the test was administered - this allows us to directly link individual student data to community variables via spatial joins

<img src="/post/2020-05-22-first-post_files/beta_1.png" alt="pale pink 2D hexagon with bright pink border; six dots are in the hexagon; four dots are yellow; one is purple; one is dark pink" width="20%"/>

## Community Level Data
At the community level, we focus primarily on economic and health-related data associated with the broad risk factors of early childhood:

  1. poverty
  2. unsafe housing
  3. domestic conflict
  4. abuse
  5. inadequate nutrition
  
These data have been collected from the Annie E Casey Foundation (Kidscount) and the ACS 2017, a 5-year survey conducted by the United States Census Bureau.


The Kidscount data, complied at the county level for each of Oregon's 36[^2] counties, include

  * percentage of children living in food insecure households
  * rates of child abuse and neglect
  * threat of harm rates
  * number of children in foster care
  * number of children in the juvenile justice system
  * rates of infant mortality
  * teen pregnancy rates
  * rates of adequate prenatal care


Variables from the ACS 2017 were collected at the census tract level. There are 834[^3] census tracts in Oregon. They include information on

  * rates of children living in households with poverty status
  * median family income
  * rates of children living in households that receive public assistance such as supplemental nutrition benefits
  * distribution of home values
  * distribution of educational attainment
  

### More Data
Moving forward, we're inquiring after data regarding other community health and economic indicators from DHS, Facebook, and additional researchers.

## Data Directory
This [documentation page](https://github.com/OR-K-Entry/k-entry/tree/master/data-documentation) provides names, descriptions, and sources for variables we have collected for our preliminary modeling.


[^1]: Anderson, D., [2019](https://djanderson07.shinyapps.io/elashiny/); Fryer & Levitt, [2004](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi365OCwdrpAhVHtZ4KHfSgAgwQFjAAegQIARAB&url=http%3A%2F%2Fpricetheory.uchicago.edu%2Flevitt%2FPapers%2FFryerLevittUnderstandingTheBlack2004.pdf&usg=AOvVaw0RQZNvZza4ZOPoJPuvQ1wn), [2006](https://www.jstor.org/stable/42705499?seq=1#metadata_info_tab_contents); García, [2015](https://www.epi.org/publication/inequalities-at-the-starting-gate-cognitive-and-noncognitive-gaps-in-the-2010-2011-kindergarten-class/)
[^2]: McClelland, Acock, & Morrison, [2006](https://psycnet.apa.org/record/2006-22456-005)
[^3]: [US Census Bureau](https://www.census.gov/geographies/reference-files/2010/geo/state-local-geo-guides-2010/oregon.html)
