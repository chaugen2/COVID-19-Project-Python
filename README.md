# COVID-19 Mask and Stay at Home Mandate Efficacy
<img align="right" src="https://user-images.githubusercontent.com/98825216/171600918-5d6c2ae7-fecc-4994-ad9e-f21e1b3e7057.jpg" alt="COVID Virus">

### Overview:
Analysis of historical COVID case and death data during stay at home mandates provide insight for the general public and health professionals to better understand if mandates are effective in mitgating COVID in the United States.

___

### Objective:
Peform data analysis of CDC data on COVID cases and deaths in relation to mask and stay at home mandatees to derive insights on the efficacy of the mandates.
____
### Data Sets:
* [U.S. State and Territorial Stay-At-Home Orders: March 15, 2020 – August 15, 2021 by County by Day](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Stay-At-Home-Orders-Marc/y2iy-8irm)
* [U.S. State and Territorial Public Mask Mandates From April 10, 2020 through August 15, 2021 by County by Day](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i)
* [United States COVID-19 Cases and Deaths by State Over Time](https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36)
* [United States COVID-19 County Level of Community Transmission as Originally Posted](https://data.cdc.gov/Public-Health-Surveillance/United-States-COVID-19-County-Level-of-Community-T/8396-v7yb)

____
### Tools:
* Pandas
* Seaborn 
* NumPy
* SciPy
* MathPlotLib
* StatsModels
________________________________


### Research Questions

#### Clarifying Questions
* Do mask and stay at home mandates impact COVID cases and deaths?
* Which states had a higher frequency of mandates? Lowest?
* Which states had the highest number of cases of COVID and deaths? Lowest?

#### Funneling Questions
* Are there higher cases of COVID and deaths in states where there are fewer mandates?  
* Is one type of mandate more effective than the other?

#### Ethical Questions
* What are the consequences of reporting on the relationship between mandates and COVID cases/deaths? Could mandates be lowered or minimized, leading to higher COVID risk? Conversely, do increased mandates lead to other issues unrelated to COVID - such as mental health?
* Are there specific privacy laws protecting data collection and storage of medically related data?
* Are there ethical concerns in identifying a state as high risk for COVID? 
______________
### Hypotheses
* Null Hypothesis: The number of COVID cases in a state without mask or stay at home mandates is equal to or less than states with mandates, two weeks after mandates are put in place.
* Hypothesis: The number of COVID cases in a state without mask or stay at home mandates is more than states with mandates, two weeks after mandates are put in place.
_____________
### Answers
According to the scatterplots generated above, stay at home and mask mandates are correlated with higher COVID cases and deaths. This may likely be that because on those days, the cases and deaths were so high, it lead states and counties to implement these policies. Looking at the data in a time series (espeically 14 days after the mandates is crucial). It is also important to add a geographical measure (state or even county level) to this story - do states with mandates have lower cases? At this point, it is only looking at the cases and mandates nationwide, not the geographical component. 

It also calls to question the ethical considerations. Taken out of context - as it is right now - it could lead people to interpret this to mean that these mandates did not work when in fact there is a great deal more to this story. 

The correlation heat map does illustrate the very strong correlation between total cases and total deaths to be very strongly correlated (which seems obvious, but it is good to confirm), so looking at total cases as a predictor of death is helpful for the hypothesis.

Photo Credit: <a href="https://unsplash.com/@cdc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">CDC</a> on <a href="https://unsplash.com/photos/k0KRNtqcjfw">Unsplash</a>
