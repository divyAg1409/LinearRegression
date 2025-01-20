# LinearRegression
BoomBike Case Study - 

Observations and explanations:
There is an increase in the bike rental count in spring and summer season , and then decrease in the bike rental count in fall and winter season.
The bike rental count distribution is higher in 2019 than in 2018.
During no holidays, the bike rental counts is the highest, compared to during holidays for different seasons.
There is no significant change in bike demand with working days and non working days.
During clear, partly cloudy weather, the bike rental count is the highest, second-highest during misty cloudy weather, and followed by 3rd highest, during light snow and light rain weather.
Outlier analysis:
(i) No outliers are present in total_count variable.
(ii) No outliers are present in normalized temp but few outliers are present in normalized windspeed and humidity variables.
Normal probability plot is a graphical technique to identify substantive departures from normality and also it tells about goodness of fit. In our normal probability plot, some target variable data points are deviating from normality.
Correlation matrix tells about linear relationship between attributes and helps us to build better models. From our correlation plot, we can observe that some features are positively correlated and some are negatively correlated to each other. The temp and atemp are highly positively correlated to each other, it means that both are carrying same information.The total_count,casual and registered are highly positively correlated to each other. So, we have ignored atemp,casual and registered variable for further analysis.
For modelling the datset, we split the dataset into train and test in the ratio of 70:30.
