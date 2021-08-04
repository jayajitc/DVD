# <p align="center"> Disability Vulnerability Dashboard </p>
<p align="center"><B>Jayajit Chakraborty and Katalina Salas, University of Texas at El Paso</B></p>
 
## Introduction
People with disabilities (PwDs) represent a vulnerable group that is significantly more likely to be injured or die than non-disabled individuals during the COVID-19 pandemic, as well as public health emergencies and various natural or human-induced disasters. Adverse impacts and health risks faced by PwDs during such events have been documented to be amplified because of their socioeconomic, demographic, and racial/ethnic minority status.
The Disability Vulnerability Dashboard (DVD) is an interactive geospatial database that can help emergency response planners, public health officials, and other stakeholders identify, visualize, and plan support for PwDs. It also serves as a web-based educational tool for learning and understanding the spatial variability, diversity, and social vulnerability of PwDs in the U.S. 
The DVD uses data from the 2019 US American Community Survey (ACS) five-year estimates to calculate and display disability-related indicators for each county. The ACS defines PwDs as members of the civilian non-institutionalized population who reported having serious hearing, vision, cognitive, ambulatory, self-care, and/or independent living difficulties. To enable mapping and analysis of relative vulnerability for PwDs, each US county is ranked with respect to all counties in the 50 US states and the District of Columbia. County rankings are based on percentile scores that can viewed and compared. The DVD contains two major components or map layers that are described below.  

## Key Components
***Type of Disability:*** This component includes the percentage of people reporting each type of difficulty (hearing, vision, cognitive, ambulatory, self-care, and independent living), percentage of PwDs reporting multiple disabilities, and the overall percentage of PwDs in each US county. All percentage estimates are based on the total civilian non-institutionalized population in the county. The definition of each disability category or variable is provided in the table below. 

| Variables  | Definition |
| ------------- | ------------- |
| % With any disability | Persons reporting at least one of the six difficulty types below |
| % 2 or more difficulty types | Persons reporting at least two of the six difficulty types below |
| % Hearing Difficulty | Deaf or have serious difficulty hearing. |
| % Vision Difficulty | Blind or have serious difficulty seeing, even when wearing glasses. |
| % Cognitive Difficulty | Because of a physical, mental, or emotional problem, have difficulty remembering, concentrating, or making decisions. |
| % Ambulatory Difficulty | Have serious difficulty walking or climbing stairs. |
| % Self-Care Difficulty | Have difficulty bathing or dressing. |
| % Independent Living Difficulty | Because of a physical, mental, or emotional problem, have difficulty doing errands alone such as visiting a doctor’s office or shopping. |

The DVD lists the percentages of people in each category, as well as their percentile ranks based on comparison with all US counties. Percentile ranking values range from 0 to 1, with higher values indicating higher percentages of PwDs in the category.

***Social Vulnerability of PwDs:*** The second component includes multiple indicators of social vulnerability for PwDs in the county, based on variables from the 2019 ACS that are organized into three dimensions: economic status, demographic status, and racial/ethnic minority status. Each US county receives a separate percentile rank for each of these three dimensions, as well as an overall social vulnerability rank for PwDs that integrates these three dimensions, as summarized in the table below.

 
| Variables  | Dimensions |
| ------------- | ------------- |
| % Below poverty PwDs | *Economic status* | 
| % Unemployed PwDs | *Economic status* |
| Median earnings ($) for PwDs | *Economic status* |
| % PwDs under 18 years | *Demographic status* |
| % PwDs 65 years or more | *Demographic status* |
| % Female PwDs | *Demographic status* |
| % Hispanic PwDs | *Minority status* |
| % Non-Hispanic non-White PwDs | *Minority status* | 

 
The percentages of each variable listed in the table above are based on total civilian non-institutionalized population, with two exceptions. % Below poverty PwDs are based on the civilian non-institutionalized population for whom poverty status is determined and % Unemployed PwDs is based on civilian non-institutionalized population in the labor force (aged 18-64 years).

***Methodology:*** For each of the three dimensions of social vulnerability for PwDs, the percentiles for the variables comprising each dimension are summed. The summed percentiles for each dimension are then rank ordered to determine dimension-specific percentile rankings (i.e., economic, demographic, and minority status). Each county receives a separate percentile score for each dimension that ranges from 0 to 1, with higher values indicating higher percentages of socially vulnerable PwDs. Overall social vulnerability scores for PwDs in each county are estimated by summing the sums for each dimension, rank ordering the counties, and then calculating an overall percentile ranking. It should be noted that calculating the sum of the sums for each dimension is the same as summing individual variable rankings. 



## Dashboard Navigation
Discuss the tools that allow access to various map layers. How to select or zoom in on any county.

Clicking on any county in the map will activate the county-specific COVID-19 information panels along the left and a pop-up display window. The COVID-19 information panels summarize…
The pop-window contains relevant information on PwDs in the county, for each map layer. 



![Add Layer](addlayer.png)

<br>

<img src = "images/countyselected.jpg" width = 200>

<br>


Click here to interact with our tool ==> [Disability Vulnerability Dashboard
](https://www.arcgis.com/apps/dashboards/8adb0362575a41d7981955bf3739de71)

## Contents
1. [Data/](./Data) This is how you reference a folder in your workflow




