# HACKTIV8 Milestone Project Phase 0 
## Full Time Data Science

Name: Fernaldy Aristo Wirjowerdojo
Batch: HCK-009

## Project Information
This project is the final output of Phase 0 in the Full Time Data Science Programme from Hacktiv8.

## Objective
This project was created to perform an analysis on Apartment prices in the 15 largest cities in Poland. Factors that may affect apartment pricing such as apartment features, apartment type and points of interest are checked to see how they influence the price.

## Dataset
The dataset is about Apartment prices in the 15 largest cities in Poland which is further enhanced by using Open Street Map to note the nearby points of interest. The data was obtained from a publicly available dataset in Kaggle via [this link](https://www.kaggle.com/datasets/krzysztofjamroz/apartment-prices-in-poland/data) by Krzysztof Jamroz. 

## Analysis
To analyse the factors mentioned above, multiple charts and statistical testing were done on the questions:
1. How does the distribution of apartment prices vary across the different cities in Poland?
2. What apartment types are common in cities in Poland?
3. How does the average price of apartments vary with the number of rooms in the apartment?
4. How do apartment prices differ based on the number of nearby points of interest?
5. How do specific features affect the pricing of the apartments?
6. Is there a significant difference in the prices of apartments with only one of the following features: Parking space, balcony, elevator, security or storage room?

## Approach for analysis
1. For questions 1 to 4, charts/plots were used to illustrate each question
2. For question 5, the Spearman correlation was used to see how the number of features an apartment has influences apartment prices
3. For question 6, ANOVA test was used on the prices of each split dataframes and then the Tukey's HSD test was used to check where the difference occurs
