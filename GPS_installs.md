### Google Play Store App Ratings and Installation Counts

There are many different categories of applications and genres. The question of which types of applications are the most frequently installed is important to discuss in order to make the important decision before developing an application that would be successful. The Google Play Store data was utilized to see which genre and category of applications had the highest installation counts.

Imports:

<img src="imgs/rc-240/1.png?raw=true"/>

The data shape was evaluated first.

<img src="imgs/rc-240/2.png?raw=true"/>

The data frame was then further processed to delete duplicate rows and dropping columns that were not pertinent to answering the question at hand. The shape of the data frame after the processing ended up with 10,358 rows and 6 columns.

<img src="imgs/rc-240/3.png?raw=true"/>

The first step in this analysis was to see which content rating has the highest number of installation counts. In order to process the data further, a few more munging steps were taken. The column names contained spaces and the spaces were first stripped. Then the rows containing NaN values were removed from Content Rating column.
<img src="imgs/rc-240/4.png?raw=true"/>


