> Ford GoBike Dataset
> By Amy Fehilly


## Dataset

> This dataset is from the Ford GoBike System data (a bike rental company), with 5054 bikes in this dataset with 1,863,721 rows and 12 features (duration, start time, end time, start station id, start station name,end station id, end station name, user type, member birth year, member gender, bike share for all trip.) The data can be found here: https://www.fordgobike.com/system-data

Data wrangling for this dataset consisted of converting the data files, combining the 12 months worth of datasets into 1 annual dataset and dropping several of the unnecessary columns that would not be used in the data analysis. 

Presentation feedback: Overall interesting analysis of the data. Feedback was mainly centred on vocabulary used - 'multivariate' and 'bivariate' data did not make sense. Viewer would like to have seen in addition, how bike trip duration correlates with weather throughout the year and the proportion of gender users as a %. 

Forums and websites used for this project:
Udacity Forum
GitHub

## Summary of Findings

> My goal was find any relationship between:
 1) Average trip times 
 2) Monthly bike ride trend and average trip times 
 3) Average trip times by gender
In the exploration, I found there was a trend between number of trips and average trip duration coming to just under 10 minutes, with some trips going up to 300 minutes and more! I found there was a surprisingly consistent minimum of bike trips throughout the year, never dropping under 200 minutes. June and July had the longest trips during those months, and January and December had fewer trips that lasted as long, however the shorted trips were consisted year long. When adding the gender variable we found female users had shorted bike trips than men consistently year long, but in June July and August, the female users bike times did increase. Male users bike times were consistently longer than women throughout the year, averaging above 400 minutes.


## Key Insights for Presentation

> FOr the presentation I focus on the main variable trip duration. I include the slide showing how the first visualistion needed a log transformation, with an explanation. I include the finished graph after the log transformation as a histogram. I then to pull in other categorical variables one by one, in a bivariate and multivariate exploration, explaining each step to the viewer and using indexes, and titles to make the graph understandable. I use scattergraphs for both the bivariate and multivariate explorations. For the multivariate test I use colour to depict the values of the third variable on the graph. 


