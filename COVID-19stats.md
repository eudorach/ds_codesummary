# COVID-19 New Cases Statistics

## Introduction

The COVID-19 pandemic began in Wuhan, China, in late 2019 and rapidly spread worldwide, significantly impacting global public health. Understanding the geographic and temporal patterns of new COVID-19 cases is crucial for informing public health responses and resource allocation.

This analysis explores the average daily new COVID-19 cases across different continents, aiming to identify regional differences in infection rates during the pandemic. The dataset was provided by Tech Academy and analyzed using Python.

### Objectives

* Compare the average number of new COVID-19 cases across continents.

* Visualize the distribution of new cases within each continent.

* Highlight continents with the highest burden of new cases.

## Data and Methods

The dataset includes daily reported new COVID-19 cases for multiple countries, grouped by continent. The key steps in the analysis were:

Data segmentation: The dataset was split into subsets based on continent.

Statistical summary: For each continent, the average (mean) daily new cases were calculated.

Visualization: Line plots and bar charts were created to compare new case averages across continents.

Python libraries such as pandas and matplotlib (or seaborn) were used for data manipulation and visualization.

Initially how the average of new cases varied within continents was performed. 
<img src="imgs/rc-243/1.png?raw=true"/>
<img src="imgs/rc-243/2.png?raw=true"/>
<img src="imgs/rc-243/3.png?raw=true"/>
<img src="imgs/rc-243/4.png?raw=true"/>
<img src="imgs/rc-243/continents.png?raw=true"/>
<br>
South America had the highest average new case rate followed by North America.

## Results
Each continents were separated into individual datasets and the average of new cases were plotted. Same methods were applied to all of the continents
<img src="imgs/rc-243/5.png?raw=true"/>
<img src="imgs/rc-243/6.png?raw=true"/>
<img src="imgs/rc-243/7.png?raw=true"/>
<img src="imgs/rc-243/8.png?raw=true"/>
<img src="imgs/rc-243/9.png?raw=true"/>
<img src="imgs/rc-243/10.png?raw=true"/>
<img src="imgs/rc-243/11.png?raw=true"/>

## Discussion
The elevated average new case counts in South and North America could reflect multiple factors, including population density, testing rates, public health policies, and virus variants. The similar analysis across continents helps provide a macro-level understanding of the pandemic's progression.

Limitations of this analysis include the use of averages which can be influenced by outliers or inconsistent reporting. Additionally, lack of normalization by population size may affect cross-continent comparisons.

## Conclusion
This exploratory statistical analysis demonstrates significant differences in COVID-19 new case averages across continents, with South America experiencing the highest average new infections in the analyzed period. Such insights are valuable for targeting public health interventions and allocating resources effectively.

