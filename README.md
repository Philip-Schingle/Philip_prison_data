## Prison_Deaths_Over_the_Last_Decade
## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

# Motivation
From 2016-2020 I was employed at a treatment facility for people with intellectual and developmental disabilities. Working with a treatement team of psychologist and psychiatrists to develop plans to help best serve the people we supported there. Medical issues were something we tackeld as a team and some issues there resulted in death for the people develped plans for. The difficulties involved in treatment and monitoring health mental and physical are important to me as well as facilitiy based operating guidelines. I felt this data project would be an interesting look into a nother sector of facility based treatment.

## Questions:
1) What are the most frequent causes of death in federal prisons?
2) Are there any trends to notice here from 2005-2024? Are inmates dying from natural causes or are deaths due to other factors? Possibly nutrition based, neglect, etc.
3)What areas of the country have higher rates of death overall or for certain causes? Are there certain states of facilities that have a high concentration of death totals?


## Problems and Hurdles
1) Parsing out the various ICD10 medical codes into more distinct medical diagnosis
2) Finding out what each 3 letter facitlity code was and which federal facitlity they belonged to.
3) The arduous process of troubleshooting the webscraping process for the adresses to each facility code from teh BOP website using the Json as a the HTML was indirectly linked to the page with the address


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) PowerBI - for creating interactive dashboard and presentation
3) Git - for version control


## Data Sources
1) Data Source: The Data Liberation Project  https://www.data-liberation-project.org/datasets/bop-federal-inmate-deaths/
2) Data Source: BOP offical website locations https://www.bop.gov/locations/list.jspm https://www.bop.gov/about/statistics/population_statistics.jsp

## Conclusion
Looking into the data, it seems that there are aspects of neglect as well as staffing issues and overcrowding of federal prisons that are affecting the increase of deaths in prison inmates generally. Some facilities with higher death rates seem to have quality control issues from a medical protocol and diligience standpoint that are creating negative outcomes for inmates, resulting in the higher death rates. The recommendation for the BOP is to look at the facilities that have lower death rates and standardize the internal operating guidelines to raise tha standard of medical health for all facilities. Researching into ways to increase staff retention is also recommended, as many issues with higher death rates seem to be due to the ratio of medical staff to inmates.
