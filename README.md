# SparkFundsInvestment
# SparkFunds Investment Data Analysis

## Brief
You work for Spark Funds, an asset management company. Spark Funds wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.

 

## Business and Data Understanding
Spark Funds has two minor constraints for investments:

It wants to invest between 5 to 15 million USD per round of investment

It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in

For your analysis, consider a country to be English speaking only if English is one of the official languages in that country

You may use this list: Click here for a list of countries where English is an official language.

These conditions will give you sufficient information for your initial analysis. Before getting to specific questions, let’s understand the problem and the data first.

 
## Strategy :

Spark Funds wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.

## Business objective:

The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing.

## Goals :
	Investment type analysis
	Country analysis
	Sector analysis

## Data Source:

We have taken real investment data from crunchbase.com, so the insights you get may be incredibly useful. 

## Tables

companies: A table with basic data of companies
rounds2: Funding round details
mapping.csv: This file maps the numerous category names in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.
