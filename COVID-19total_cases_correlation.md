### COVID-19 Total Cases Correlations
COVID-19 pandemic started in Wuhan, China and quickly spread across the globe. Many research and studies were conducted to help better slow down and hopefully, cease the spread. The dataset was given by Tech Academy and the data was analysed using Python. 

Python Imports:
<img src="imgs/rc-245/1.1.png?raw=true"/>
To best analyze the changes that happened over time, the 'date' column of the dataset was separated into 'year', 'month', and 'day' columns.
<img src="imgs/rc-245/1.png?raw=true"/>

The most pressing question was whether the total number of vaccinations had any effect on the number of total cases. 
<img src="imgs/rc-245/2.png?raw=true"/>

Vaccines were not developed until late 2020/early 2021 so the data was processed to only include the year 2021.
<img src="imgs/rc-245/3.png?raw=true"/>

The overall trend of the vaccinations over time was first performed. The graph shows an exponential trend with the number of vaccinations over time.
<img src="imgs/rc-245/4.png?raw=true"/>
<img src="imgs/rc-245/vaccinations and total cases in 2021.png?raw=true"/>

The number of total cases also does increase, however, it shows a linear trend.
<img src="imgs/rc-245/13.png?raw=true"/>

The slopes of both total vaccinations and total cases were computed. The slope of average total vaccinations is 23,139,266/month whereas the slope of average total cases is 250,448/month. 
<img src="imgs/rc-245/15.png?raw=true"/>
<img src="imgs/rc-245/14.png?raw=true"/>

There is a positive correlation between the total cases and total vaccinations. It appears that the increase in number of total cases is causing the vaccination numbers to increase.
<img src="imgs/rc-245/16.png?raw=true"/>

The next criteria examined was how smoking affects the total number of cases. 
<img src="imgs/rc-245/5.png?raw=true"/>
<img src="imgs/rc-245/6.png?raw=true"/>
<img src="imgs/rc-245/7.png?raw=true"/>
<img src="imgs/rc-245/8.png?raw=true"/>
<img src="imgs/rc-245/female smokers and total cases.png?raw=true"/>
<img src="imgs/rc-245/9.png?raw=true"/>
<img src="imgs/rc-245/male smokers and total cases.png?raw=true"/>
<br>
The correlation coefficients for these columns were also computed, which showed that there are no strong correlation between
smoking and the number of total COVID-19 cases. However, there is a weak correlation between female smokers and total cases (0.29), suggesting that female smokers are more likely to be infected with the virus. 

<img src="imgs/rc-245/10.png?raw=true"/>

Age was another factor that was analyzed.
<img src="imgs/rc-245/11.png?raw=true"/>

The outliers were removed for a more reliable result. There appears to be a trend, with increased number of cases with advancement of age.
<img src="imgs/rc-245/12.png?raw=true"/>
<img src="imgs/rc-245/med age and total cases.png?raw=true"/>

Correlation table was created which shows weak correlation between the total cases and age, in all of the different age groups. People who are older are more likely to be infected with the virus. 
<img src="imgs/rc-245/17.png?raw=true"/>