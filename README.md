# Nigeria-COVID-19-Data-Analysis-Using-Python
Data Scientist Microdegree Capstone Project
# Project Overview
Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered virus, and it has affected major parts of the world. Nigeria, a West-African country, has also been affected by the COVID-19 pandemic after recording its first case on 27th February 2020.

Nigeria is a country with 37 states - Federal Capital Territory included- and a fast-growing economic environment with about 200 million citizens. COVID-19 has affected several country activities as the country steadily progressed from its first case to shutting down major airports, state-wide lockdown, curfews, and reviving its economy.
In this project, I have employed data science & analytics skills to collect data, explore the data, perform analysis, create visualizations, and generate insights. 
# Steps
* The first thing I did was to collect data needed for analysis, using python's beautiful soup I was able to scrape data from NCDC covid-19 official website.
* I downloaded data from The Johns Hopkins University Center for Systems Science and Engineering repository, they publish daily data on confirmed, death and recovered cases across different countries in their repository.
* I also made use of the Nigeria Community Vulnerability Index data, Real Domestic Gross Product Data, and the State Budget Data.
* After data collection, I cleaned and performed exploratory analysis on the data.
# Insights
I was able to derive the following insights:
  * The top ten states in terms of confirmed covid-19 cases by Laboratory test are: Lagos, FCT, Kaduna, Plateau, Rivers, Oyo, Edo, Ogun, Kano, Ondo.
  * The top ten states with the highest number of discharged covid-19 patients are: Lagos, FCT, Kaduna, Plateau, Rivers, Oyo, Edo, Ogun, Kano, Ondo.
  * The top ten states with the highest number of deaths are: Lagos, Edo, FCT, Oyo, Kano, Rivers, Delta, Kaduna, Ondo, Plateau.
  * The highest number of confirmed cases recorded in Nigeria was on the 23rd of January, 2021. On this day, Nigeria recorded 2,464 covid-19 cases.
  * The highest number of recovered cases recorded in Nigeria was on the 4th of October, 2020. On this day, 11,188 patients recovered from covid-19.
  * Nigeria recorded the highest number of deaths on the 16th of June, 2020. 31 covid-19 patients lost their lives.
  * After merging NCDC data with Nigeria Community Vulnerability Index data, I was able to detect a negative relationship between number of cases confirmed in Lab and overall CCVI Index that is the higher the number of confirmed cases the lower the overall community vulnerability index in the states except in FCT.
  * There is a direct relationship between population density and number of cases confirmed in the lab, the higher the population density the higher the number of cases confirmed in the laboratory.
  * There is also a negative correlation between Age Index Score and number of cases confirmed in Lab with Age Index Score and Number of Deaths that is when we have a low Age index score there are more confirmed cases and more number of deaths and vice versa.
  * Enugu, Abia, Imo are the first 3 states with the highest number of people with Acute IHR that is people that got infected and are expected to require acute care, these 3 states are also seen to have a low health index score, but the number of deaths in these three states are low, but Lagos with a very high number of deaths has a low health index score and a high percentage of people who got infected and are expected to require acute care. This implies that despite the good health system in Lagos, more people still die.
  * People with low age index score, are at lower risk of needing acute care when infected but people with high age index score are at higher risk of needing acute care when infected.
  * There is a negative relationship between Number of Cases Confirmed in Lab and Socio-Economic Index Score.
  * There is a direct relationship between Epidemiological Index Score and Number of Deaths with Epidemiological Index Score and Number of Patients discharged.
  * There is a slight negative relationship between Fragility Index Score and Number of Cases Confirmed in Lab.
  * The GDP of quarter 1 and quarter 2 of each year are always lesser than the GDP of quarter 3 and 4. 2020 had the lowest GDP for quarter 2 compared to quarter 2 of previous years due to the impact of covid 19 on the economy.
# Executive Summary
[Link to executive summary file](https://github.com/adejumobiesther/Nigeria-COVID-19-Data-Analysis-Using-Python/blob/main/Executive_Summary1.docx)



