# Analysis of Kickerstarter Campaign Funding

Perform analysis and visualizations on Kickstarter data to uncover trends related to campaign funding success in Microsoft Excel.

## Analysis to Identify Factors that Determine Campaign Funding Outcomes

This analysis looks at how different Kickstarter play campaigns in the Theater category perform based on Kickstarter campaign launch dates and campaign funding goals. The analysis is created to help a playwright find ways in which the goals set and the month of the launch correlate to the success of the campaign. 
With that in mind, this analysis is focused on funding success based on launch date and goal amounts.

### Analysis Background
This data analysis was initially used to help an up and coming playwright determine if there are specific factors that would help make her Kickerstarter campaign successful. Intially, this analysis was used to help the playright plan her own Kickerstarter campaign and set it up for success. Using the initial analysis, she looked to understand campaigns from start to finish and to setup her own Kickstarter campaign to mirror other successful campaigns in the same category.


### Kickstarter Analysis Data
The data for this analysis was sourced from https://www.acrowdfundingwebsite.com and includes:
* 4114 international Kickstarter campaigns started from 2009 to 2017. 
* Successful, canceled, failed and live Kickstarter campaigns
* Kickstarter goals dollars in the data ranged from $1 to 100,000,000.00. 
* Kickstarter pledged dollars in the data ranged from $1 to 100,000,000.00. 

## Analysis Outcomes

The analysis outcomes provide trends related to campaign funding success identifying how different Kickstarter play campaigns in the Theater category perform based on Kickstarter campaign launch dates and campaign funding goals

### Analysis of Outcomes Based on Launch Date
* Creates a Years column of data using the Excel Year() function which extracts the year from the data column 'Date Created Conversion' for each included campaign.
* Creates a pivot table made off the KickerStarter data
* Configures the pivot table creating filters for filtering the data by Parent Category and Years
* Pivot table is filtered on "Parent Category" to only show the data for "theater" for this analysis
* Pivot table data is filtered to include only "successful", "failed" and "canceled" campaign outcomes for this analysis
* Pivot table row labels have been changed to display months of the year and the data was sorted to present successful campaigns first for this analysis
* Line chart was created and formated with a title from the pivot table which visualizes the relationship between outcomes and launch month

![Theater Outcomes versus Launch Date](/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
* Goal ranges were created to calculate outcome goals
* Calculates outcome counts by goal ranges using COUNTIFS() function including:
  * Number of Successful
  * Number of Failed
  * Number of Canceled
* Calculates total projects by goal ranges using SUM() function
* Calculates outcome percentages by goal ranges using Excel operators and formating including:
  * Percentage Successful
  * Percentage Failed
  * Percentage Canceled
* Line chart was created and formated with a title from the calculations which visualizes the relationship between the outcomes and the goal ranges

![Outcomes vs Goals](/Outcomes_vs_Goals.png)

### Analysis Challenges and Difficulties Encountered
Challenges and difficulties for this analysis work came down to tools and rules.
1. Tools: Relying on a README report to provide and summarize my finding is not my go-to presentation mode. Keeping the analysis work focused on using Excel (and the internet) as my only analysis tools was restrictive for me. Excel is part of my go-to toolset for data analysis but not usually my only data analysis tool. I typically would use other tools in combination with Excel in my analysis work.
2. Rules: This analysis had a fixed set of instuctions, formating requirements and scope to emphasize learning particular Microsoft Excel skills and was completed in a fixed timeframe of 2 weeks. 

## Results

### Outcomes based on Launch Date
Campaign launch date has some impact on the sucess of Theater play projects getting funded. There are certain launch months that provided better outcomes than others:
1. Most theater play campaigns were successful
   * Most theater play campaigns were successful if launched in months other than December. 
   * Success of launching Theater play campaigns in other months was between 57% and 63% successful.
2. Launching theater play campaigns in May and June is popular and usually successful
   * Most Theater play caimpaigns launched in the months May and June and plays launched in these month were 66% successful. 

## Launch Date Success Measures
* Most successful month to launch a Theater play project is June
* Least successful month to launch a Theater play project is December
* Theater play projects launched in other months were mostly successful as well
 
### Outcomes based on Goals
There are certain ranges of goals that perform better than others. The highest percentage of success was for goals $1000 or under. The second highest percentage of success was for projects with goals in the $35000 to $49,000 range. There were two projects with goals in excess of $50,000 that were successfully funded. 

#### 1. Average Goals (Means)
* Successful US Theater play projects on average had goals of a little over $5000
* Failed US Theater play projects on average had goals of a little over $10,000

#### 2. Median Goals
* Successful US Theater play projects had median goals of a little over $3000
* Failed US Theater play projects had median goals of a little over $3000

### Dataset limitations
There were some dataset limitations for the analysis. 

Dataset limitations of note include:
1. Aged data: This analysis was performed in September 2021. Data is from Kickstarter campaigns created between 2009 and 2017. (pre-COVID19 epidemic) Patterns may have changed in more recent years.
2. Dataset size: 4114 international Kickstarter campaigns
3. Outliers: Campaign data contains some outliers that should be reviewed when using the results of this analysis

## Additional useful visualization -Tables and Graphs
Recommendation for additionals tables and charts include:
 * Adding a box and whisker Chart to identify Theater play data outliers for successful and failed campaigns could be useful in this analysis.
 * Adding chart to look at successful and failed launchs be weeks for the year and day of the week to provide more detailed launch date recommendations
 * Adding chart to look at this data by country could provide further insights on country differences and different recommendation for each

## Recommendations
Launching a Theater play campaign on Kickstarter is likely to be successful but there are factors that should be considered around launch dates and goals that can funding success. 

### Launch Date Recommendations 
Launching a Theater play campaign in the month of June if possible is recommended. May is also a good time to launch a Theater play campaign. Launching a Theater play campaign in December should be avoided if possible. All other months for launches were relatively successful as well. 


### Campaign Goal Amount Recommendations 
Keeping campaign goals less than $1000 if possible is recommended for highest funding success. Other goal ranges can be successful as well.

## References
* Examples of README files and notes about how to write them. https://github.com/inessadl/readme
* Examples of similar analysis performed on the same dataset and with similar limitations. https://github.com/leblabac/kickstarter-analysis
* Timestamp converter. https://www.epochconverter.com/
* What is a timestamp. https://websiteseochecker.com/blog/what-is-timestamp/
* Help with Calculated Field & Item (Formulas) in a Pivot Table. https://excelchamps.com/pivot-table/calculation-in-pivot-table/
* Help with coding varied coding and coding concepts https://stackoverflow.com/
