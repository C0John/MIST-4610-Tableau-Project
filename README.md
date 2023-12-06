# MIST-4610-Tableau-Project

## Team Name
The Dream Team

## Team Members
1. Andrew Neely [@AndrewN2024](https://github.com/AndrewN2024)
2. Carter Johnson [@C0John](https://github.com/C0John)
3. Nate Jarrow [@NateJ123](https://github.com/NateJ123/)
4. Andrew Zhang [@drewteriyaki](https://github.com/drewteriyaki)
5. Mark Zhang [@zhmark9](https://github.com/zhmark9)

## Description of dataset:
Our dataset details all real estate sales in the state of Connecticut between Oct. 1st, 2001, and Sept. 30th, 2020 (using the "grand list year"). We obtained this dataset from [https://catalog.data.gov/dataset] as suggested. The dataset includes several columns of quantitative and qualitative data that can be used for data analysis and visualization using Tableau. The file includes the town, property address, date of sale, property type (residential, apartment, commercial, industrial, or vacant land), sales price, and property assessment as columns. Each row in the table is an individual sale. These data points allow us to analyze trends related to time, location, and categorical attributes of each sale. As an example, in the town of Ashford, there is a residential property on 390 Turnpike Rd which has an assessed value of $253,000 and an actual sale amount of $430,000. Its serial number is 20002 and was listed as a single-family residence on 10/2/2020 with a sales ratio of 0.5883.

## Question 1:
Which cities in Connecticut had the highest average real estate sale price? How did the average sale price change over time for each city? This question directly references the sales amount (also referred to as sales price) column in the data set with the use of the AVG function.

### Importance:
Understanding which Connecticut cities have the highest real estate prices and how these prices change over time is crucial for economic decision-making. This information guides both individual and institutional investors in making wise investment choices, informs government planning for housing and infrastructure, and helps address affordability challenges. Real estate prices also serve as indicators of broader economic trends and consumer confidence, influencing business and residential decisions. In essence, this data is vital for informed economic decisions and assessing the overall economic health of each city.

Higher real estate prices can often signify desirable places to live, own land, or conduct commercial business. These areas are often filled with amenities, historical significance, and a variety of entertainment. You can often find theaters, museums, high-end restaurants, and vibrant city, state, or national parks. On the contrary, lower real estate prices have the opposite effect. The importance of knowing this data in a cultural context is to see where a city could improve. For example, if a city was continuously on the lower end of average sale prices compared to other cities, governmental bodies can use these figures and keep track of them when making zoning changes for new industries.


![avg_sales_price](https://github.com/C0John/MIST-4610-Tableau-Project/assets/141379047/1177c085-bb14-4799-9dd2-44e4d1d5ec87)


Our first visualization for Question 1 (above) illustrates the average sales price, by town, for all of the towns in the data set. We have decided to only show the towns above $700k sales amount in order for the illustration to be readable and to maintain relevance. With that said, an analysis can be done for any other parameter. As you can see, Willington has the highest average sales price and Fairfield has the lowest average sales price in this illustration. Many societal factors can be analyzed and inferred with the use of this one number and can also be used in conjunction of other outside data in order to collect a holistic analysis of why the numbers are the way they are. Using this sales price data, we are able to analyze it further in our second illustration.


![sales_price_over_time](https://github.com/C0John/MIST-4610-Tableau-Project/assets/141379047/bacc3387-fe98-4190-91ae-be93f908877e)


Our second visualization for Question 1 (above) illustrates the average sales price trend for different towns. In this illustration, we've set a parameter of >$1.2M for readability and relevance. Using the town of Greenwich as an example, the average sales price fluctuates many times, sometimes drastically. The importance of this visualization is to see how external factors can influence these trends and provide up-to-date insights on the economic status of these towns and the state of Connecticut as a whole. A very helpful insight that is provided by this graph is when the market crash of 2008 occurred. As you can see on Greenwich's line, the housing price was high in 2006 and 2007 and then plummeted in 2008. This is a great example of how this visualization can be utilized to provide stakeholders with an understandable model of the status of average sales prices.


## Question 2:
What is the average sales ratio for each property type? What does the disparity between assessed value and actual sale amount indicate for certain property types? This question directly references the sales ratio column with the use of the AVG function. The assessed amount and sales amount columns are also used as well.

### Importance:
Economically, by finding the average sales ratio for each property type and the disparity between them, one can assess market efficiency. Disparities between assessed values and actual sales value amounts can indicate inefficiencies in property valuation methods which would then in turn potentially impact taxation and market functioning. For example, a sales ratio below 1.0 can lead to overvaluation in the tax assessment process. Another example, if the sales ratio was above 1.0, this can benefit the buyer since they bought it for less than what it is worth but could create shortfalls for local governments if properties are consistently undervalued. Using the average sales ratio, governments can assess policies and regulations to examine their effectiveness. It is also important to consider how investors may assess property. By finding the average sales ratio, investors can determine where investing would be best for their business outcome.

Socially, inaccurate assessments can impact homeownership, particularly low-income buyers or marginalized groups. In addition, different socioeconomic groups may be impacted by a disproportionate ratio. Lastly, uncovering discrepancies can allow governing bodies to minimize the deterioration of public trust in the system.

Developmentally, the average sales ratio disparity can affect decision-making related to land use, zoning, and infrastructure development. In other words, the disparity can determine if decisions need to altered regarding zoning, land use, and infrastructure development. The ratio is crucial in urban development and planning in order to allocate resources efficiently. In addition and just by having the average sales ratio for each property type, governing officials are provided insights into each property type's ratio and can then make inferences on the reasons behind why each ratio is that particular value. Without this ratio value and the visualization, these officials would have no way of garnering helpful data to make informed decisions.


![Graph 3](https://github.com/C0John/MIST-4610-Tableau-Project/assets/148258373/d90e22b2-f506-4f96-8b09-8b480f507c9a)


Our first visualization for Question 2 illustrates the average sales ratio for each property type. As the graph shows, the Single Family property type has the highest average sales ratio - slightly over 0.7. In addition, the Apartments property type along with a couple of others are around 0.5 and 0.6. This means for these property types, the sales amount was above the assessed value. These ratios indicate slight disparities and must be monitored to ensure fair and accurate assessments. Note that all property types fall below 1.0. This is due to the removal and exclusion of extreme outliers that are not relevant and would skew the data visualization.


![Graph 4](https://github.com/C0John/MIST-4610-Tableau-Project/assets/148258373/a9e97844-cd95-44e0-9d9b-34102fdc5f7b)


Our second visualization for Question 2 illustrates the disparity between the average assessed value and the average sale amount. Please note that the dollar amount ($, x-axis) is slightly different for each tablel. This is to ensure that the visualization is easy to read. Referring back to the Single Family and Apartments property type mentioned in the first visualization, the graph accurately portrays that Single Family properties are assessing at ~$280,000 while selling for almost double and Apartment properties are assessing for ~$1,283,325 while selling for ~$2,734,071. Having these two graphs side by side allows an analyzer to understand which properties have higher and lower average sales ratios and provides insights to estimated assessed values and actual sale amounts. Rather than just a sales ratio number, this visualization further describes the disprarities and provides estimations.


## Manipulations applied to the data set for analysis:
Our data set contained several extreme outliers that were removed in the filtering process using Tableau. We were able to remove this outliers to get a more accurate representation of the average sales ratios. Without their removal, we would have extreme average ratios that would not only contradict the other visualizations and graphs, but show confusing and skewed tables. Other than manipulations, the only 'calculations' we used were using the AVG function in Tableau.


## Tableau Packaged Workbook

Please see the Tableau Packaged Workbook below - the workbook was too large to upload to Github directly (file size limit 25MB).
https://drive.google.com/file/d/1l2Eq6fc7ZzjthgKAeMc0EEpLAOT-ubS1/view?usp=sharing
