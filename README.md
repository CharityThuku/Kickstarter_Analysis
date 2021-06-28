 # An Analysis of Kickstarter Campaigns

## Quantitative and Qualitative data acquired from 4000 campaigns
- This data is gathered into excel and using formulas, we are able to compact the data to find hidden trends within the data. By calculating central tendency, measures of spread and creating graphs, the data becomes more understandable. 

## The purpose
- Purpose of the project is to gain knowleddge on how to use excel and its formulas to find trends within large sets of data.

## Analysis

### Analysis Based on Launch Date
- For this analysis we were asked to use the year() function to find the year each project was created. I created a pivot table to show the breakdown of the successful, failed and canceled projects based on the parent category and year created. This allowed us to see the breakdown of the theatre projects created in each month and the outcomes of those projects.Lastly, a line chart was created to see the trend of outcomes during the year. 

![Outcomes Based on Launch Data](https://user-images.githubusercontent.com/85714314/123565331-20be6100-d782-11eb-8f1f-dc5334d66ff0.png)


### Analysis Based on Goals 
- For this analysis, we were ask to use the countifs() function to get the number of cells in a range that met specific goal standards. Using this function, we created columns of successful, failed and canceled outcomes. The sum() function was used to get the total number of projects in each range. We calculated the percentage of projects that were successful, canceled and failed. Lastly, a line chart was created to view the trend of outcomes based on goals. 

![Outcomes Based on Goals](https://user-images.githubusercontent.com/85714314/123565560-f620d800-d782-11eb-8d48-e1539e5648e0.png)

### Challenges
- The challenges I encountered during this project included copying and pasting and,using the countifs() function. I had trouble pasting into new worksheets making sure to keep the original formatting of the excel sheet. Using the countifs() function was a bit challenging because I didn't know how to use it using ranges. I used the help function on excel to help me learn how to choose the correct pasting method and how to add ranges using this function.

## Results

### Conclusions from Outcomes Based on Launch Date
- Looking at the graph, there are alot more successful outcomes, than failed or canceled outcomes. The middle of the year is the best time to launch a project, with May having the highest success rate. Toward the end of the year, the success rate begins to decline. The failed and canceled outcomes are fairly stable during the year.

### Conclusions from Outcomes Based on Goals
- The percentage of canceled outcomes based on goals is 0%. The percentage of failed and successful outcomes is equal to 100%. When the goal is less than a $1000 or between the range of $25,000-$29,000, the project is most likely to be successful. In all the other ranges, the project is more likely to fail. 

### Limitations
- This dataset is very large, in order to discover any information from it, it has to be filtered and formatted which takes a lot of time.

### Possible tables/graphs
- We could create a table to show the average donation per country. We could also create a graph to show pledged amount vs number of backers.

