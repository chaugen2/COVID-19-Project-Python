# Efficacy of Mask and Stay at Home Mandates on COVID Cases in the United States
<img align="right" src="https://user-images.githubusercontent.com/98825216/171600918-5d6c2ae7-fecc-4994-ad9e-f21e1b3e7057.jpg" alt="COVID Virus">

### Overview:
Analysis of mask mandate and stay at home recommendation data to determine whether mandates are effective in mitigating COVID in the United States.
___

### Objective:
Peform data analysis of CDC data on COVID cases in relation to mask and stay at home mandatees to derive insights on the efficacy of the mandates.
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

### Resources and Research
* [Why Masks Work, but Mandates Haven’t](https://www.nytimes.com/2022/05/31/briefing/masks-mandates-us-covid.html). _New York Times_, May 31, 2022. 
* [First Confirmed Case of COVID-19 Found in US](https://www.history.com/this-day-in-history/first-confirmed-case-of-coronavirus-found-in-us-washington-state). _History_, January 21, 2020.
* [President Trump Confirms 1st U.S. Coronavirus Death; U.S. Heightens Travel Warnings](https://www.npr.org/2020/02/29/810722517/seattle-area-patient-with-coronavirus-dies?t=1654713407066&t=1656259469043). _National Public Radio_, February 29, 2020.
* [Science Brief: Community Use of Masks to Control the Spread of SARS-CoV-2](https://www.cdc.gov/coronavirus/2019-ncov/science/science-briefs/masking-science-sars-cov2.html). _CDC_, December 21, 2021.
* [Evaluating the effectiveness of countywide mask mandates at reducing SARS-CoV-2 infection in the United States](https://www.degruyter.com/document/doi/10.1515/jom-2021-0214/html?lang=en). _Journal of Osteopathic Medicine_, January 21, 2022.
* [Timing of State and Territorial COVID-19 Stay-at-Home Orders and Changes in Population Movement — United States, March 1–May 31, 2020](https://www.cdc.gov/mmwr/volumes/69/wr/mm6935a2.htm). _CDC_, September 4, 2020.
_____________________
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
### Findings
Hypohesis Testing: The correlation between mask mandates and COVID cases per 100K is 0.42 and between stay at home mandates and COVID cases per 100K is 0.30. These relationships are weak, so the null hyothesis cannot be rejected.


Photo Credit: <a href="https://unsplash.com/@cdc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">CDC</a> on <a href="https://unsplash.com/photos/k0KRNtqcjfw">Unsplash</a>
