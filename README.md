Research Framework Summary

	- Scrapping and Data Collection
	- Data Cleaning (outlier management, filling of missing values)
	- Exploratory Data Analysis 
	- Predictive Modelling (regression analysis, prediction accuracy)
	- Discussion (interpretation, sensitivity analysis, limitations)
	- Conclusion

 Functions created and used
 	
	1. fill_in : To fill in missing values with computed financial ratio and industry median
 	2. convert_to_numeric : To transform string representations of numbers into numeric format
	3. count_hashtags : To count the no of hashtags present in a Twitter profile bio
 	4. categorize_user_name : To categorize user_name based on company name

Loading and Saving Data:
	
 	- Load training and testing Twitter Followers data 
	- Load independent variables (financial) data
 	- Load independent variables (non financial) data
  	(twitter's users profile dataset is scrape from Twitter ([https://twitter.com](https://twitter.com/home?lang=en)))
	- Submit prediction to Kaggle to test prediction accuracy

Data Files:

	"Data/Followers_train.csv"
 	(training dataset provided on Kaggle (<https://www.kaggle.com/competitions/followers/data>))
	"Data/Followers_test.csv"
 	(test dataset provided on Kaggle (<https://www.kaggle.com/competitions/followers/data>))
	"Data/Followers_sampleSubmission.csv"
	"Data/profile_info.csv"
 	(twitter's users profile dataset is scrape from Twitter ([https://twitter.com](https://twitter.com/home?lang=en))	(
	"Data/stock_price.csv"
 	(From S&P Global Market Intelligence \> S&P Compustat Global)
	"Data/key_developments.csv"
 	(From S&P Capital IQ \> Companies \> Key Developments)
  	"Data/Financials.csv"
   	(From Compustat - Capital IQ \> North America \> Fundamentals Quarterly)
	"Data/Financials Ratios.csv"
 	(From Compustat - Capital IQ \> North America \> Financial Ratios Suite by WRDS)

Project Specific Requirement:

	Predicting the expected number of Twitter followers for US corporations
	A set of daily counts of Twitter followers for selected companies during the year 2017 will be provided
	Tasked with modelling the changes in followers and will need to forecast this out beyond the time frame of the provided data
 	Allowed to use any outside data to build the model
  
For more details, refer to the code and functions provided in the file.
