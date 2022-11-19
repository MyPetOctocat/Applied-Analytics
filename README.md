# Applied-Analytics
Code and Notebooks for analysis of used car dataset


## What is mobile.de

Mobile.de is a German online marketplace for cars. It specializes primarily on C2C used car sales. With heavy marketing campains mobile.de could secure a position as the go-to plattform when it comes to buying cheap cars. Like many tech companies like uber, airbnb and ebay, their business model is built around providing a hub where user meet and engage in service/product transactions. Unlike for example car dealerships their job is not to sell cars, but provide a plattform that users engage in. Not micromanaging sales make this platform sustainable, but at the same time sites like mobile are highly reliable on the [network effect](https://de.wikipedia.org/wiki/Netzwerkeffekt). Companies like these first need to heavily invest in building a large community, before they can focus on turning a profit.

## Business Model Canvas

![Analytics_BMC](https://user-images.githubusercontent.com/61428610/202824749-21960b68-6efe-4a5b-a4d5-05bd07916998.png)

## Data Science in the context of mobile.de

Since mobile.de is essentially a centralized platform with a very large user base, they have a lot of possibilities to extract data from their website, which in return can be used to do various types of data analysis. Data analysis give insight in how to make their site more user-friendly. One goal could be to reduce the time a user has to find their offer. This could for example be done via cluster analysis: A user gets allocated to a cluster with same car tastes which get shown similar offers. Since mobile.de is a platform their main objective is to keep people engaged on their site/App. Without an active user-base a business like mobile.de is not sustainable and machine learning has the potential to leverage this problem, by getting better understanding of their users and the ecosystem that they built on this site.

## Project Outline

- EDA (Explorative Data Analysis)
- General Data Preprocessing
- Regression
- Cluster Analysis
- Classification

## Conclusion

As anticipated, one of the most time consuming aspects in this project was the data preparation. Because of the nature of web-scraping, data is often inconsistent and faulty. Another error component are the humans that create these car sales that can be seen by unrealistic, exorbitant car prices (probably joke offers). Especially with such data it is always a struggle to decide what data to remove and what data to keep. On one hand the goal should be to keep as much data as possible, on the other hand one wants to assure data quality. The worst would be to remove seemingly "faulty" data that actually had structure in it (NMAR).

Implementing a ML algorithm is one thing, but extracting meaning out of them is another huge task, especially if the data seem to be relatively 'all over the place' like this craigslist dataset. This became especially apparent in with clustering. Even looking at the dataclouds visually one could see that the relationship between all data points are very complex.

Nevertheless, this project was despite its hurdles a big learning experience in how to work with data that seems unusable at first glance. And in the end there was some very interesting insight to be had. 
