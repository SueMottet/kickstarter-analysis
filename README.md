# Analysis of Kickerstarter Campaign Funding

Perform analysis and visualizations on Kickstarter data to uncover trends related to campaign funding success in Microsoft Excel.

## Analysis to Identify Factors that Determine Campaign Funding Outcomes

This analysis looks at how different Kickstarter play campaigns in the Theater category perform based on Kickstarter campaign funding goals and campaign launch dates. The analysis is created to help a playwright find ways in which the goals set and the month of the launch correlate to the success of the campaign. 
With that in mind, this analysis README report is focused on funding success based on launch date and goal amounts

### Analysis Background
This data analysis was initially used to help an up and coming playwright determine if there are specific factors that would help make her Kickerstarter campaign successful. Intially, this analysis was used to help the playright plan her own Kickerstarter campaign and set it up for success. Using the initial analysis, she looked to understand campaigns from start to finish and to setup her own Kickstarter campaign to mirror other successful campaigns in the same category.


### Kickstarter Analysis Data
The data for this analysis and the visualizations was sourced from https://www.acrowdfundingwebsite.com
* included 4114 international Kickstarter campaigns started from 2009 to 2017. 
* Successful, canceled, failed and live Kickstarter campaigns
* Kickstarter goals dollars in the data ranged from $1 to 100,000,000.00. 
* Kickstarter pledged dollars in the data ranged from $1 to 100,000,000.00. 


## Analysis Outcomes

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
* Creates a Years column of data using the Excel Year() function which extracts the year from the 'Date Created Conversion' for each included campaign
* Creates a pivot table made off the KickerStarter data
* Configures the pivot table creating filters for filtering the data by Parent Category and Years
* Pivot table is filtered on "Parent Category" to only show the data for "theater" for this analysis
* Pivot table data is filtered to include only "successful", "failed" and "canceled" campaign outcomes for this analysis
* Pivot table row labels have been changed to display months of the year and the data was sorted to present successful campaigns first for this analysis
* Line chart was created and formated with a chart title from the pivot table which visualizes the relationship between outcomes and launch month
![Theater Outcomes versus Launch Date](/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

![Outcomes vs Goals ](/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
1. Relying on a README report to provide and summarize my finding is not my go-to presentation mode.
2. Trying to keep my analysis work focused on using Excel (and the internet) as my only analysis tools was also challenging for me. 
Excel is part of my go-to toolset for data analysis but not usually my only data analysis tool. I typically would use other tools in combination with Excel in my analysis work.
3. This analysis was perform per a fixed set of instuctions, formating and scope to emphasize learning particular skills:


## Results

### Outcomes based on Launch Date
- What are two conclusions you can draw about the Outcomes based on Launch Date?
## Data distribution - successful campaigns versus failed campaigns
 - How is the data distributed
   - Mean -  if every data point contributed the same amount what would that amount be
   - Median - where is the midpoint of the data
   - Mode - what values show up the most
   - Is the data skewed left or right
## Data spread
  -Range
  -Variance
  -Standard deviation
  - quartiles
  


### Outcomes based on Goals
- What can you conclude about the Outcomes based on Goals?
## Data distribution - successful campaigns versus failed campaigns
 - How is the data distributed
   - Mean -  if every data point contributed the same amount what would that amount be
   - Median - where is the midpoint of the data
   - Mode - what values show up the most
   - Is the data skewed left or right
## Data spread
  -Range difference between max and min values of data set
  -Variance how far data points are from the center
  -Standard deviation
  -interquartile range
  - quartiles - data percentiels - divided in 4 ranges lowest to highest
### Dataset limitations
- What are some limitations of this dataset?
1. Aged data. Data is from Kickstarter campaigns created between 2009 and 2017. (pre-COVID19 epidemic) Patterns may have changed in more recent years.
2. Dataset size - 4114 international Kickstarter campaigns
3. Outliers

## Additional possibly useful visualization 
- What are some other possible tables and/or graphs that we could create?
  - Measures of central tendency 
    -Mean, Median Mode

## References
