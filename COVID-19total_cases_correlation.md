# COVID-19 Total Cases Correlations Analysis

## Introduction

The COVID-19 pandemic originated in Wuhan, China, and rapidly expanded worldwide, prompting extensive research to understand and control its spread. This analysis uses a dataset provided by Tech Academy, processed and analyzed in Python, to explore relationships between COVID-19 total cases and several potential influencing factors.

## Data Preparation

To facilitate time series analysis, the dataset’s date column was split into separate year, month, and day columns. Given that vaccines were introduced late in 2020 and early 2021, the analysis focusing on vaccination effects was limited to data from the year 2021.

Python Imports:
<img src="imgs/rc-245/1.1.png?raw=true"/>
<img src="imgs/rc-245/1.png?raw=true"/>

## Vaccination and Total Cases Over Time
* The total number of vaccinations administered over 2021 exhibits an exponential increase.

* In contrast, the total number of COVID-19 cases shows a linear increase over the same period.

Linear regression slopes were computed to quantify these trends:

* Average monthly increase in total vaccinations: ~23,139,266

* Average monthly increase in total COVID-19 cases: ~250,448

<img src="imgs/rc-245/2.png?raw=true"/>
<img src="imgs/rc-245/3.png?raw=true"/>
<img src="imgs/rc-245/4.png?raw=true"/>
<img src="imgs/rc-245/vaccinations and total cases in 2021.png?raw=true"/>
<img src="imgs/rc-245/13.png?raw=true"/>
<img src="imgs/rc-245/15.png?raw=true"/>
<img src="imgs/rc-245/14.png?raw=true"/>

## Correlation between Vaccinations and Cases

A strong positive correlation was observed between total COVID-19 cases and total vaccinations during 2021. This may reflect that:

* Increased case counts motivated more individuals to seek vaccination.

* Public health campaigns accelerated vaccination efforts as cases rose.

Thus, while vaccines aim to reduce case numbers, their rollout often follows infection trends, explaining the positive correlation.
<img src="imgs/rc-245/16.png?raw=true"/>

## Smoking and COVID-19 Cases
To investigate lifestyle risk factors, correlations between smoking prevalence and total COVID-19 cases were examined:

* No strong correlations were found between overall smoking rates and COVID-19 cases.

* A weak positive correlation (r = 0.29) was identified between female smokers and total COVID-19 cases, suggesting a possible increased risk or susceptibility in this subgroup..

<img src="imgs/rc-245/5.png?raw=true"/>
<img src="imgs/rc-245/6.png?raw=true"/>
<img src="imgs/rc-245/7.png?raw=true"/>
<img src="imgs/rc-245/8.png?raw=true"/>
<img src="imgs/rc-245/female smokers and total cases.png?raw=true"/>
<img src="imgs/rc-245/9.png?raw=true"/>
<img src="imgs/rc-245/male smokers and total cases.png?raw=true"/>
<br>
<img src="imgs/rc-245/10.png?raw=true"/>

## Age and COVID-19 Cases
Age was analyzed as a risk factor:

* Outliers in the age data were removed to improve reliability.

* A trend emerged showing increased total cases with advancing age.

* Correlation analysis confirmed weak positive correlations between age groups and total cases, implying older populations may be more vulnerable to infection.
<img src="imgs/rc-245/11.png?raw=true"/>
<img src="imgs/rc-245/12.png?raw=true"/>
<img src="imgs/rc-245/med age and total cases.png?raw=true"/>
<img src="imgs/rc-245/17.png?raw=true"/>

## Discussion
This analysis highlights several important relationships:

* The rapid scale-up of vaccination efforts in 2021 occurred alongside continued increases in COVID-19 cases, reflecting complex dynamics between public health responses and viral spread.

* Smoking, particularly among females, may have a modest association with COVID-19 susceptibility, meriting further targeted investigation.

* Older age groups appear more affected by COVID-19, consistent with known clinical vulnerability.

Limitations include:

* Potential confounding variables not accounted for (e.g., socioeconomic status, healthcare access).

* Correlational analyses do not establish causality.

* Data quality and reporting inconsistencies could affect results.

## Conclusion

* Vaccination efforts in 2021 accelerated rapidly, yet total COVID-19 cases continued to increase linearly during this period.

* A strong positive correlation between vaccinations and cases likely reflects reactive public health behavior rather than vaccination causing increased infections.

* Smoking shows minimal correlation with case counts, with a slight signal in female smokers.

* Older age correlates weakly with higher COVID-19 case numbers, reinforcing the need for protective measures in these populations.

Future analyses could explore additional factors, employ causal modeling, and incorporate more granular demographic data to deepen understanding of COVID-19 risk factors.

