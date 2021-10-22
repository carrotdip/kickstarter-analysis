# Kickstarting with Excel

## Performing analysis on Kickstarter data to uncover trends to determine how similar fundraising campaigns turned out based on their launch date and funding goals.

### The purpose of this analysis project was to ascertain various relationships between an abundance of data points that can predict how Louise's play _Fever_ will fare. These correlations were produced by analyzing how well other Kickstarters, specifically plays, prospered based on their launch date and funding goals. This will give Louise an idea of how successful her play _Fever_ will turn out based on her fundraising goal and launch date.

### Analysis of Outcomes Based on Launch Date
The analysis was performed by first determining theater outcomes based on their launch dates. This was done by filtering the data to only include information relating to theater. Campaigns that were live and incomplete were also filtered out. 
![text](https://github.com/carrotdip/kickstarter-analysis/blob/e9d9352f7438ad9075a3240b94870218a91decc7/Screen%20Shot%202021-10-21%20at%206.48.47%20PM.png)
![text](https://github.com/carrotdip/kickstarter-analysis/blob/e9d9352f7438ad9075a3240b94870218a91decc7/Screen%20Shot%202021-10-21%20at%206.49.09%20PM.png)
The launch dates were provided in the UNIX timestamp format, which was converted to the MMDDYYY format using a simple equation to convert the time into days and formatted the time into a date. 
![text](https://github.com/carrotdip/kickstarter-analysis/blob/a388f0d66b7decdd73b840500b3cdb326715a0e0/Screen%20Shot%202021-10-21%20at%206.55.46%20PM.png)
Then, a pivot table was created to organize the results based on the month the fundraising campaigns were created. 
![text](https://github.com/carrotdip/kickstarter-analysis/blob/e9d9352f7438ad9075a3240b94870218a91decc7/Screen%20Shot%202021-10-21%20at%206.45.14%20PM.png)m
From this pivot table, a line graph was utilized to visualize the results.
![text](https://github.com/carrotdip/kickstarter-analysis/blob/f2dcf9816123c1bec2a1d9c3c49e991f962d77c1/Theater_Outcomes_Vs_Launch.png)

### Analysis of Outcomes Based on Goals
The outcomes of the Kickstarter data was also analyzed by the proposed goal of the fundraising campaigns. The goals of the Kickstarter campaigns were first divided into different ranges and the number of successful, failed, and cancelled campaigns were calculated using the =COUNTIFS function on Excel. 
![text](https://github.com/carrotdip/kickstarter-analysis/blob/e9d9352f7438ad9075a3240b94870218a91decc7/Screen%20Shot%202021-10-21%20at%206.50.14%20PM.png)
The equation was also able to filter the data collected in the US and regarding plays specifically. Once these numbers were determined, the percentage of successful, failed, and cancelled Kickstarters was calculated, and visualized in the following graph.
![text](https://github.com/carrotdip/kickstarter-analysis/blob/cce9f7f97e530c5b7feb86d76e137020e98e2505/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Some challenges I faced during this analysis project was understanding what specific symbols meant in Excel. In the modules, we were simply given commands to do without an explanation of "why". For example, we were given instructions to create a pivot table and add certain values in the filters, legend, axis, and values. It took a while for me to understand which values to include to organize the data the way I desired. I felt that I would not be able to create a pivot table from another set of data. There were also times Excel automatically added a value to a category when I dragged one value to the right spot, which altered the graph and results. I was happy with the graphs in the modules that showed what the graphs should look like to determine whether I was on the right track, but did not understand why I had to delete categories I did not add. 
The equations in Excel were also hard to grasp because they included symbols in the example without definition. Luckily, I was able to figure out which each symbol corresponded to on my own, but I do wish it was clear in the modules. For example, the '!' symbol would be referring to a specific spreadsheet within the Excel file. 

## Results
What are two conclusions you can draw about the Outcomes based on Launch Date? + limitations
The Outcomes based on Launch Date suggests that Kickstarter theater outcomes tends to be the most successful during the month of May. There is a sharp increase of successful plays in May, however, there appears to be a increase in failed theater outcomes as well. Some limitations of this analysis would be that the visualized data is based on the number of Kickstarters during each month. There is an overall increase of theaters launched during May that can....

- What can you conclude about the Outcomes based on Goals?
US plays that have funding goals less than $5,000 tend to fare better than plays with higher funding goals. This is shown by the consistent decrease in successful outcomes as the goal increases. There are some limitations in this data that causes the percentages to flunctuate with goals over $25,000. Some limitations of the dataset would be the limited sample size of the data used in this analysis due to the distinct parameters used. The sample size of the entire data set is far from limited, however, due to the nature of the project, the focus was on US plays specifically. Due to the narrow focus, during the analysis of US play outcomes based on goals, there were not many data points for plays with goals greater than $25,000. This causes the percentages to become increasingly unrealiable.

- What are some other possible tables and/or graphs that we could create?
