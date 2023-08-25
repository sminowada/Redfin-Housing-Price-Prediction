# Redfin-Housing-Price-Prediction

Last webscrape: 11/24/2023

Webscraped Berkeley CA housing info from redfin of sold houses using Beautiful Soup 

Used SciKit Learn to create a linear regression model using sold housing data to predict prices of houses currently on market

Model underestimated a lot of the houses, that could be due to high mortgage rates or inflation

Would add more variables such as walkability score in the future to have more location input as a variable

References:
* https://www.robertthasjohn.com/post/predict-housing-prices-with-linear-regression-using-scikit-learn
* https://github.com/NGO-Xuan/Scraping-Data/blob/main/OneCity-Redding.ipynb

# Files

**forSale.csv:** contains scraped data from houses currently for sale

**housesSold.csv:** contains scarped data from houses that have already been sold

**redfinCleaningAnalysis:** contains data cleaning for our files as well as data analysis

**redfinWebscraping:** contains code for webscraping a redfin page. Redfin gives you a maximum of 360 listings that you can view. Also, this code can take a while since it does a request for each listing which is why I saved the outputs to csv files. 
