![alt text][logo]*^	

# Prepared by LAST CALL CONSULTING (LCC)
[logo]: http://www.reyesbeveragegroup.com/Global/Logos/RBG-wheat-shield.png

## Beer Case Study Dataset

* Dataset Download link: [Dataset](https://openbeerdb.com/)

Abstract:  The BeerStudy dataset was created by merging a beer and brewery dataset presented in source. This new dataset was created to answer business questions asked by a fictional management team at Reyes Beverage Group.


|BeerStudy  Dataset  |             |          |
--- | --- | ---
*Datasets Merged* | Breweries.csv | Beers.csv	    
|Attributes   |Categories, Factors, Integer, Numerical| No. of Attributes= 10|	
|Deliverables| Values of ABV, IBU, Plots by State|---------|
|Missing Values| Present

## Source

Case Study Partners
* William Holt (williamholt@smu.edu)
* Yejur Singh Kunwar (ykunwar@smu.edu)

The dataset was provided by Dr. Faizan Javed through files section of 2DS for this case study. The original dataset is located in this link for this study. https://openbeerdb.com/


## Data Set Information

The BeerStudy dataset consists of 10 different variables assigned created by merging Brewery.csv and Beer.csv dataset. 

BeerStudy: Data frame containing 2410 observations with 10 variables

|Variables  | Types | Range | Information 
--- | --- | --- | ---
 |BreweryID   |Integer|  1-558| Unique Brewery ID|
 | BeerName   | Factor| 2305 levels | Names of Beers|
 | BeerID      | Integer | Values  | Unique Beer ID|
 | ABV         | Numerical | Values (ABV rating) with 62 NA's | Alcohol by Volume|
 | IBU         | Integer | Values (IBU rating) with 1005 NA's| Bitterness Unit |
 | BeerStyle   | Factor| 100 levels  | Styles of Beer|
 | Ounces      | Numerical | 12, 16| Ounces of Beer|
 | BreweryName | Factor | 551 levels |Names of Brewery|
 | BreweryCity | Factor | 384 levels |Location of Brewery|
 | BreweryState| Factor | 51 levels |State of Brewery|

***Note: Any Brewery located in same state but different city is treated as unique brewery

## Codes and Conclusion
This explains the codes and conclusions derived from the Case Study markdown file shared in GitHub.

1. Read Breweries.csv and Beers.csv data, changed the names to human readable attributes.
2. Answered breweries present in each state by assigning it to dataframe named StateBreweries.
3. Assigned dataframe BeerStudy by merging Breweries.csv and Beers.csv data by unique BreweryID, verified 2410 observations with 10 columns. 
4. Reported NA's in each column.
5. Computed median for ABV and IBU for each state and represented in bar chart.
6. Determined state with maximum alcoholic beer (ABV) and most bitter beeer (IBU).
7. Summarized ABV variable.
8. Plotted scatterplot to determine any correlation between IBU and ABV. Proved with Pearson correlation.

## Other information
FOR STUDY PURPOSE ONLY, NO BUSINESS EFFECTS OR SUGGESTIONS\
(*^This is just a case-study done for MSDS 6306, does not intend to represent any logo, company, or suggest any findings.)\
LAST CALL CONSULTING (LCC) is fictional company created for this case study purpose only.
