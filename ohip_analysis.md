### Oral Health Impact Profile-14 (OHIP-14) Analysis on Postoperative Patients
Orthognathic surgery is a surgical procedure performed on the jaws to correct their misalignment. Mild misalignment of the teeth or the jaws does not impact the quality of life significantly. However,
severe misalignment can cause difficulty with average daily living (ADL) functions such as biting through and chewing food. It can also cause frequent tongue or cheek biting which can cause discomfort
in the mouth. Orthognathic surgery is an elective but an important surgery that can improve the quality of life in a person with severe dentofacial deformity. One way to gauge how the quality of life 
changes after surgery is by Oral Health Impact Profile (OHIP) questionnaires. The question posed is, is there a significant improvement in the OHIP scores after surgery? 

The initial stage of data collection was done by exporting data from the REDcap database in Excel/CSV form. 

First I imported the necessary libraries for the analysis. I also ensured that the working directory was correct to continue proceeding with the necessary file imports and data analysis. 
<img src="imgs/ohip/OHIP_1.PNG?raw=true"/>

The CSV file was imported using pandas. The initial dataset was sizable with 932 columns. 
<img src="imgs/ohip/OHIP_2.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_4.PNG?raw=true"/>

The columns containing the word 'ohip' was isolated and created into another dataframe with the respective identifiers.
<img src="imgs/ohip/OHIP_5.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_6.PNG?raw=true"/>

For data cleaning purposes, rows with all NaN values were dropped. 
<img src="imgs/ohip/OHIP_7.PNG?raw=true"/>

With the smaller dataframe, the column names were displayed to remove unnecessary ones.
<img src="imgs/ohip/OHIP_8.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_9.PNG?raw=true"/>

The last column, ohip_score_interpretation, was missing some values so the scores are stratified according to the standard scoring ranges. 
<img src="imgs/ohip/OHIP_10.PNG?raw=true"/>

Basic statistics was displayed for a general overview. 
<img src="imgs/ohip/OHIP_11.PNG?raw=true"/>

Next came data visualization to see the data distribution. Box and whiskers plot was created to display the distribution of the score stratification. POM6 distribution was more spreadout and there were more people experiencing mild discomfort with their oral health. However, by month 12, most people had remorted little to no symptomatology and only one person reported moderate symptoms. 
<img src="imgs/ohip/OHIP_12.PNG?raw=true"/>
<img src="imgs/ohip/ohip_score_distribution.png?raw=true"/>

The next step was to see how the patients progress and change over time.  
<img src="imgs/ohip/OHIP_13.PNG?raw=true"/>
<img src="imgs/ohip/ohip_change_pom6_pom12.png?raw=true"/>

Because the initial dataset only had POM 6 and POM 12 information, initial visit data was added to the dataset for a more comprehensive assessment. 
<img src="imgs/ohip/OHIP_15.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_16.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_17.PNG?raw=true"/>

The next step for analysis was to group the time points together to plot how things change from initial to POM 6 to POM 12. For this particular analysis, only those with all three time points were included.
<img src="imgs/ohip/OHIP_18.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_19.PNG?raw=true"/>
<img src="imgs/ohip/ohip_score_alltime.png?raw=true"/>

Then I wanted to break it down from initial to POM 6 and POM 6 to POM 12 for a more detailed look at the data. Initially, only the subjects with both data points were assessed then all of the subjects were visualized.
<img src="imgs/ohip/OHIP_20.PNG?raw=true"/>
<img src="imgs/ohip/ohip_score_initial_pom6.png?raw=true"/>
<img src="imgs/ohip/OHIP_21.PNG?raw=true"/>
<img src="imgs/ohip/ohip_change_pom6_pom12.png?raw=true"/>
<img src="imgs/ohip/OHIP_22.PNG?raw=true"/>
<img src="imgs/ohip/ohip_initial_pom6_all.png?raw=true"/>
<img src="imgs/ohip/OHIP_23.PNG?raw=true"/>
<img src="imgs/ohip/ohip_pom6_pom12_all.png?raw=true"/>

Once the data was visualized to better understand the data, the statistical analysis was performed. Because it is not a normalized data and it is the same subjects with multiple data points, Wilcoxon test was chosen for analysis. The statistical test showed that initial to POM 6 OHIP score change from initial visit (preoperative) to POM 6 was statistically significant wheras the score change from POM 6 to POM 12 was not. 
<img src="imgs/ohip/OHIP_24.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_25.PNG?raw=true"/>
<img src="imgs/ohip/OHIP_26.PNG?raw=true"/>

The data analysis shows that the oral health improvement can be expected within 6 months after surgery and for the symptoms or impact to stabilize after postoperative month 6. However, this dataset is also a small cohort so a more robust data collection would be advisable to make this conclusion more reliable. 
