# Kickstarting with Excel

## Louise's project: two technical new analyses: outcomes based on goals and outcomes based on launch date

- This project has the purpose to help Louise on plan her campaign by making the data more readable, searchable and to perform analysis that can bring her some insights.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
-  In this analysis we can visualize campaign outcomes based on launch date. 
- For that, I first created a new column in the Kickstarter work book and I labeled it "Years".
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/6eebd31fddddd0ce419fa7c1049d5633cdec9753/Screen%20Shot%20years%20column.png)
- Then I created a pivot table from the KickStarter worksheet:
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/532e206acf244f680f69773d8b48d69bcf387bd5/Pivot%20Table%20without%20filter.png)
- I filter the "Parent Category" to show only the data from the "theater" and that is how I created the line chart from this pivot table: 
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/db18df1f4605a2a98c6416ac0597fd1559ef908f/Screen%20Shot%20of%20theater%20Outcomes.png)

### Analysis of Outcomes Based on Goals
- For this analysis I had to create a new worksheet in the KickStarter work book and I labeled it as a "Outcomes Based on Goals". 
- In the new sheet I created eight new columns (*Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled*), then only for the "Goal" column I created dollar-amount ranges.
- I also used the COUNTFS function to populate the "Number Successful," "Number Failed," and "Number Canceled", I used the SUM function to populate the "Total Projects" column and at the end I calculate the percentage of successful,failed and canceled projects as you can see in the screenshot below:
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/db2ddfa3f3fa3ac4f8c14aca912d4c0966043248/Screen%20Shot%20New%20Columns%20with%20COUNTIFS.png)
- After that I created a line chart to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis:
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/14397853aa78f5e3e7c1558326ecb3da6b2a1057/Screen%20Shot%20of%20Outcomes_vs_Goals%20chart.png) 

### Challenges and Difficulties Encountered
- For the Analysis of Outcomes Based on Launch Date, I found it difficult to visualize Row Labels by month instead of quarter. So, the solution was to group monthly. After researching this in the excel tutorial, I found out that I had to select the rows with the data and click on the right side of the mouse. It worked out well as in the screenshot below:
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/3a5093c5654224ddb918539307a87a4dca4749b7/Screen%20Shot%20of%20Group%20and%20ungroup.png)

## Results

- Based on the chart "Outcomes based on Launch Date" I can conclude that historically, campaigns that were launched in the month of May had the highest number of successes. 
My second conclusion is that January and others months around have the highest rate of project that got canceled and seasonally speaking, I believe that based on this information, winters are bad for starting a campaign.
- For that reason, I recommend to Louise that she starts her campaign in the month of May.

- In the analysis of Outcomes based on Goals we can conclude that the most successful projects had the lower goals, there were less than 5000. 

## Limitations of the dataset:
- The limitation of this dataset is that it could be incomplete, since that Kickstarter only has data available from 2012 until 2017. Which means that it has passed 4 years since this data was collected and now people's behavior may have changed after a pandemic, such as priorities and others. 
## Recommendation for additional tables or graphs:
- However, we can could create a table that include a column with "country" and filter it for successful projects in any specific country and Louise can have more chances to obtain success. Below, I did it for US and that is how it looks like: 
![This is an image](https://github.com/KandiJayana/kickstarter-analysis/blob/a679e302ec8c3c39d4650e06e9fbcc749c214fb2/Screen%20Shot%20Outcomes%20vs%20Goals%20US%20Projects.png)

