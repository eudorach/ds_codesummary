### Google Play Store App Ratings and Installation Counts

There are many different categories of applications and genres. The question of which types of applications are the most frequently installed is important to discuss in order to make the important decision before developing an application that would be successful. The Google Play Store data was utilized to see which genre and category of applications had the highest installation counts.

Imports:

<img src="imgs/rc-240/1.png?raw=true"/>

The data shape was evaluated first.

<img src="imgs/rc-240/2.png?raw=true"/>

The data frame was then further processed to delete duplicate rows and dropping columns that were not pertinent to answering the question at hand. The shape of the data frame after the processing ended up with 10,358 rows and 6 columns.

<img src="imgs/rc-240/3.png?raw=true"/>

The first step in this analysis was to see which content rating has the highest number of installation counts. In order to process the data further, a few more munging steps were taken. The column names contained spaces and the spaces were first stripped. Then the rows containing NaN values were removed from Content Rating column. The data types of each column was evaluated. 
<img src="imgs/rc-240/4.png?raw=true"/>

In order to proceed with further analysis, the installation count needs to be converted to a numeric value. The data was processed as follows:
<img src="imgs/rc-240/5.png?raw=true"/>

The number of installation was divided by 1000 to make the numbers smaller to work with. Then the data frame was grouped by the content rating and averaged to show the highest number of installation counts. The averages were plotted which shows the highest number of average installation count with 'Everyone 10+' rating

<img src="imgs/rc-240/6.png?raw=true"/>
<img src="imgs/rc-240/7.png?raw=true"/>

The next analysis was done to see which category within the content rating 'Everyone 10+' had the highest number of installation count. 

<img src="imgs/rc-240/8.png?raw=true"/>
<img src="imgs/rc-240/9.png?raw=true"/>
<img src="imgs/rc-240/10.png?raw=true"/>
<img src="imgs/rc-240/11.png?raw=true"/>
<img src="imgs/rc-240/12.png?raw=true"/>
<img src="imgs/rc-240/13.png?raw=true"/>

The conclusion drawn was that the most popular content rating in the Google Play Store was 'Everyone 10+' and within that rating, the most downloaded application category was 'Games'. Therefore, the type of application that will most likely succeed will be games rated 'Everyone 10+'. 
