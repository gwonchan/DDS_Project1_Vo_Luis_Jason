# Case Study 01 - Beers and Breweries - Budweiser

## Introduction  
We will be taking the Beers and Breweries datasets and perform an EDA and KNN model testing. Our audience is the CEO and CFO of Budweiser. We will be finding any relationships between ABV and IBU and we will be answering 9 main questions.

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


## Credit (Project Members)
Luis Garcia  
Jason Yoon  
Vo Nguyen
