# kickstarter-analysis

# Study to uncover any hidden trends in crowdfunding industry

## Overview of Project
This study mainly focuses on two different relationships. First, the relationship between Theater’s outcomes based on launch date and also last but not least the relationship between Play outcomes based on goals. 
### Purpose
This study will help to understand how different campaigns fared in relation to their launch dates and their funding goals. 

### Analysis and Challenges

For below mentioned two analysis “Date Created Conversion” column was created from Unix based time format provided in “launched_at” column. Then years were determined from “Date Created Conversion” column to study the trend of theater over the time period of nine years. A pivot table was created. The main criteria were considered successful, failed and canceled from outcomes column for theater over the time period. A line chart was created to visualize the trend.

The second analysis was done to study out come based on goals for different plays. Several ranges were taken to present the data with interval of amount 4999. Only first row interval was taken as 999. Entire data sheet was distributed between twelve ranges. Based on these twelve-range percentage successful, failed & canceled plays were determined. A line chart was created to visualize the trend. Both line charts are shown below      
       
### Analysis of Outcomes Based on Launch Date

This analysis was done by creating a pivotable. Pivot table consists of value from launched date and outcomes of theater. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85950281/124354807-e3236300-dbdb-11eb-8c2d-f02fdd1ba1f2.png)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85950281/124357987-31406280-dbec-11eb-92d0-6349677bf55a.png)


### Analysis of Outcomes Based on Goals 

This analysis was done by retrieving Percentage of Successful, failed & canceled plays with relation to goal range  

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85950281/124354854-2bdb1c00-dbdc-11eb-94d3-f80212b79601.png)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85950281/124358015-546b1200-dbec-11eb-8095-a0b4e21f8f8a.png)


### Challenges and Difficulties Encountered

For these two analyses no significant challenges or difficulties were encountered. Though the extreme values found in goal column may cause mean to change significantly. We may get asymmetrical distribution. Also variance, standard deviation, quartiles 3 & 1 may change significantly. 

### Results

From the chart “Theater Outcomes Based on Launch Date” we can see that theaters have highest success value during month of may. After may trend starts to decline and during december the difference between success and fail is less compare to may.       
From the chart of “Outcome Based on Goal” we can see that the plays having goal amount between $1000 to $5000 have highest success rate.    

### Limitations of this dataset

Dataset has some values which may affect mean. Data will be skewed to the right. Unix time stamp is not humanly readable, time stamp was converted to a familiar date format to read the date data. Category and sub category provided in same column.  

### Some other possible tables and/or graphs that we could create

We can determine outcome based on individual years to check yearly trend. We can compare success, fail, cancel of play with some other parent category. We could have used bar chart or pie chat to represent the data also. 
