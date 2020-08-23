# Metro Bike Share
## by Ashwin Paramashivan


## Dataset

This data can be found from the following website: https://bikeshare.metro.net/about/data/ 

This website has various files from 2016 all split up into 4 quarters for each year and also has data from various large cities in the United States. 
Here I have focused on Los Angeles, California for the Year of 2019. I downloaded 4 quarter csv files from the website and imported them into pandas to create a dataframe.

With 4 different large dataframe I had to merge them into single dataframe in order to do some data cleaning. I have added two new columns to the dataframe which are seasons and months and they were extracted from datetime. 


## Summary of Findings

The dataframe has 17 columns. The main purpose of this project is to determine the number bike trips conducted in the year 2019. 

Univariate Explorations: I observed that shorter duration is one of the cause for major bike trips. Mostly standard bikes were used more than electric and smart cars. In the summer months there were many bike user than in the cooler months. Many people preffered one way trip rather than round trips.

Bivariate Explorations: Here I came up with relationship with two attributes. One interesting thing I found is that standard bikes are more often used in the winter than the electric bikes. This can be due to the fact that electric bike are more efficent in the summer months and dangerous in the winter months. Smarter bikes were not used ofter because they were more expensive. Regardless of any variable, most trips were short and one way.

Multivariate Explorations: I have found that durations, season, months and bike types were the main cause for the increasing demand in bike trips.

## Key Insights for Presentation

1. Distrubition of Duration:
he shorter the duration then there are more numbers of bike trips conducted. This could be due to the cost associated with the trip length. For instance, longer duration would be expensive, so that is why many prefered shorter duration.
2. Months with the most bike trips according to bike types:
n the months of August, September and October there has been more trips conducted with electric bikes than standard bikes. That is because in Los Angeles those are the hottest months and with sufficient amount of sunlight, the electric bikes charges better. They require less effort for pedelling but they come at a higher price. So many people wanted to go with the cheaper option. In the months of January to April, there were very little number of people using electric bikes because it is not highly recommended to use electric bikes in the winter. The trips conducted with smart bikes is less because they cost more than standard and electric bikes.
Summary of my findings:
The main reasons for the increasing demand of bike trips is due to shorter duration, warmer months, bike types and trip route category.

## Licences
This project is made for Udacity Data Analytics course.
