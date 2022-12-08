# Kickstarting with Excel

## Overview of Project
This project is an analysis performed for Louise.  She is a budding entrprenuure who is interesting in crowdfunding campaigns of verious types in the field of theatrical presentation.  While she started a campaign for a play "Fever" she is moving on with other adventures.  Wisely Louise is making decisions based on realiable and relevant historical data.

### Purpose
As Louise moves to her next project we will provide her with specific analysis on results of different campaigns success factors based on lauch date.  Is there a better season or month?  Did campaigns in certain months have more success?

Also Louise want more detailed analysis on the success factors based on the funding goals.  How much is too much?  Do larger goals increase or decrease the probability of a successful campaign.  Is there a sweet spot between low and higher goals that will give her a clearer pathway to a successful campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In the analysis based on launch date we viewed the data set by month of the campaign launch and looking at the "successful", "Failed", and "canceled" campaigns.  The scope of the analysis was theatrical campaigns over the complete timefame of the data available.

Using a pivot table to narrow and filter the data and the accompanying chart we can clearly show the results of this analysis.

Using the analysis tools at hand this project will provide Louise with the planning of her future campaign.

The raw data can be found in the Excel workbook linked below on the workshet entitled "Kickstarter". The data Analysis can be found on the worksheet entitled "Theater Outcomes by Launch Date".  This file can be downloaded.
*   https://github.com/SusanFair/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx

The challenge of drilling down to months instead of years was solved by adjusting the rows category in the PivotTable Fields configuration. 
               ![PivotTable Rows field](https://github.com/SusanFair/kickstarter-analysis/blob/main/Resources/PivotTable_Field_Config.PNG)


### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
In the analysis based on campaign funding Goal sizes we viewed the data set by funding dollar amount within specified monitary ranges.  The scope of the analysis was theatrical plays campaigns which were successful over the complete timefame of the data available. Using the analysis tools at hand this project will provide Louise with the planning of her future campaign.

Using a counting formulas to narrow and filter the data we derived a table and the accompanying chart so as to clearly show the results of this analysis.

The raw data can be found in the Excel workbook linked below on the workshet entitled "Kickstarter". The data Analysis can be found on the worksheet entitled "Outcomes Based on Goals". This file can be downloaded.
*   https://github.com/SusanFair/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx

The goal ranges used were as follows:
* 1000 to 4999
* 5000 to 9999
* 10000 to 14999
* 15000 to 19999
* 20000 to 24999
* 25000 to 29999
* 30000 to 34999
* 35000 to 39999
* 40000 to 44999
* 45000 to 49999
* 50000 or More

The challenge in this analysis was the new formula for COUNTIFS where there were multiple criteria used to filter the count.  The provided video gave helpful guidance in creating the required filters.

## Results

### Conclusions of analysis of Outcomes based on Launch Date?
From the analysis we can see that Louise is on the right track!!  With the category of Theatre there were more Successful campaign in general that Failed and Canceled campaigns.  Looks like Theatre campaigns are hot right now!

Other valuable conclusions can be made.  The campaigns that launched in the month of May had the highest number of successful campaigns.  This was closely followed by the months of June and then July.   

It can also be noted that November and December had the lowest number of successful campaigns. 

As a general notation, the months of May and June had the highest number of Successful campaings however they also had the highest number of Failed campaign.  In general those months simply had the highest number of campaigns overall.  Further analysis of other factors would therefore be necessary to discern specific success factors.

The following chart will show the overall results:

![Outcomes Success based on Launch Date](https://github.com/SusanFair/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch_final.png)


### Conclusion of anlysis of Outcomes based on Goals?
The analysis for successfull outcomes based on campaign goal sizes was a bit broader.  Campaign goals below $1000 had high success rantes with 75% being successful.  However other ranges  saw similar rates with goals between 35000 to 39999 and 40000 to 44999 each have a success rate of 67%.  It was also evident that the higher ranges had distintcly lower success with ranges over 45000 having a success rate of under 14%.

It should also be noted that the failed campaigns were the mirror image of the successful ones.

The following chart will show clearly the overall results:
![Outcomes vs Goals](https://github.com/SusanFair/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)


### Limitations of this dataset?
There are a few limitation of this dataset.
* Current data - In the Theater category the most recent year of data is 2017 with only 31 campaigns in that year.  Having more current data, reflecting the current economy would be advisable to gain meaningful analysis.



### Options for further analysis
- What are some other possible tables and/or graphs that we could create?
Since in the Theater Outcomes by Launch Date the months of May and just had the highest number of Successful campaings however they also had the highest number of Failed campaign.  An analysis of the highest % of campaigns per month would be an interesting analysis.  This would remove the prevelence of campaign starts and provide an actual success % by month.

Another interesting and possibly helpful analysis would be on the number of backers and how this affects the success or failure of campaigns.