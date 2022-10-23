# Case Study 01 - Beers and Breweries - Budweiser

## Introduction and Purpose
In this project, we will analyze the alcohol contents(ABV) and bitterness(IBU) of craft beers in the breweries of United States. We will perform an EDA and introduce the KNN classification model of beer types using ABV and IBU values and verified with beer samples in the market including Budweiser using R. Additionally, we will be analyzing the top 3 breweries in the United States, and finding the average ABV and IBU of those breweries. As we use the average ABV and IBU values, we will address to Budweiser on what is the best type of alcholic drink should Budweiser produce in Texas, based on our KNN model. This assumes that we are talking to Budweiser in Texas, and that they are trying to produce a beer in Texas. 

## Datasets
The Beers dataset contains a list of 2410 US craft beers and Breweries dataset contains 558 US breweries. The datasets descriptions are as follows. We will be using R to perform statistical analysis.

### Beers.csv:  
Name: Name of the beer
Beer_ID: Unique identifier of the beer  
ABV: Alcohol by volume of the beer  
IBU: International Bitterness Units of the beer  
Brewery_ID: Brewery id associated with the beer  
Style: Style of the beer  
Ounces: Ounces of beer  

### Breweries.csv:  
Brew_ID: Unique identifier of the brewery  
Name: Name of the brewery  
City: City where the brewery is located  
State: U.S. State where the brewery is located  

## Questions
1.	How many breweries are present in each state?  
2.	Print the first 6 observations and the last six observations the merged file.  
3.	Address the missing values in each column.  
4.	Compute the median ABV and IBU for each state. Plot a bar chart to compare.  
5.	Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?  
6.	Comment on the summary statistics and distribution of the ABV variable.  
7.	Is there an apparent relationship between the bitterness of the beer and its alcoholic content?  
8.	Budweiser would also like to investigate the difference with respect to IBU and ABV between IPAs and other types of Ale.   
9.  If Budweiser was to release a type of alcoholic drink for Texas, what would be the best type of drink based on our KNN model and market analysis? We are first going to find the Market Share Analysis based on the total number of beers produced to find the average ABV and IBU values of the top three breweries, then run our KNN model to determine the type of beer based on that ABV and IBU values for the Texas market. 

## Table of Contents
1. Beers and Breweries Dataset  
2. RMD file  
3. Knit html file  
4. Codebook  

## Conclusion
In our data analysis, we have analyzed the datasets of Brew and Breweries focused on the alcohol contents(ABV) and bitterness(IBU) in the United States. In our KNN model, we decided to include our N/A using the impute functions. We chose the KNN model because of the inexpensiveness, popularity, and effectiveness with high accuracy. We introduced the classification model of beer types using ABV and IBU values and verified with beer samples in the market including Budweiser. We suggested in making IPAs for Budweiser because we use the average IBU and ABV values in our KNN model to predict IPA. We noticed that there could be a bias in our model. The top three breweries could possibly make more IPAs. 

## Credit (Project Members)
Luis Garcia  
Jason Yoon  
Vo Nguyen
