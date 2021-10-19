# Kickstarting with Excel

## Performing analysis on Kickstarter data to uncover trends to determine how similar fundraising campaigns turned out based on their launch date and funding goals.

### The purpose of this analysis project was to ascertain certain relationships between an abundance of data points that can predict how Louise's play _Fever_ will fare. These correlations were produced by analyzing how well other Kickstarters, specifically plays, prospered based on their launch date and funding goals. This will give Louise an idea of how successful her play _Fever_ will turn out.

### Analysis of Outcomes Based on Launch Date
The analysis was performed by first determining theater outcomes based on their launch dates. This was done by filtering the data to only include information relating to theater. Campaigns that were live and incomplete were also filtered out. The launch dates were provided in the UNIX timestamp format, which was converted to the MMDDYYY format using a simple equation to convert the time into days and formatted the time into a date. Then, a pivot table was created to visualize the outcomes based on the month the fundraising campaigns were created, by showing the outcomes based on the month the fundraising campaign was started.
![text](https://github.com/carrotdip/kickstarter-analysis/blob/f2dcf9816123c1bec2a1d9c3c49e991f962d77c1/Theater_Outcomes_Vs_Launch.png)

### Analysis of Outcomes Based on Goals
The outcomes were also analyzed by the proposed goal of the fundraising campaigns. The goals of the campaigns were first divided into different ranges and the number of successful, failed, and cancelled campaigns were calculated using the =COUNTIFS function on Excel. The equation was also able to filter the data collected in the US and regarding plays specifically. Once these numbers were determined, the percentage of successful, failed, and cancelled Kickstarters was calculated. 
![text](https://github.com/carrotdip/kickstarter-analysis/blob/cce9f7f97e530c5b7feb86d76e137020e98e2505/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Some challenges I faced during this analysis project was understanding what specific symbols meant in Excel. In the modules, we were simply given commands to do without an explanation of "why". For example, we were given instructions to create a pivot table and add certain values in the filters, legend, axis, and values. It took a while for me to understand which values to include to get the data I wanted. There were also times Excel automatically added a value to a category that was not supposed to be there, which altered my graph. I was happy with the graphs in the modules that showed whether I was on the right track. 
The equations in Excel were also hard to grasp because they included symbols in the example without definition. Luckily, I was able to figure out which each symbol corresponded to on my own, but I do wish it was clear in the modules. For example, the '!' symbol would be referring to a specific spreadsheet within the Excel file. The X:X which corresponded to the range of columns, which was also not clear in the explanation. 
The last challenge I faced in 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
![image](https://user-images.githubusercontent.com/92421274/137826710-c9c8d7ff-ac37-4ead-adf8-a71e54024523.png)
