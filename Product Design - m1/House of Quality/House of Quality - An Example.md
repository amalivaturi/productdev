	In this example, we are looking to build a demand forecasting tool and planner
## Overview
1.) Gather customer requirements
2.) Research & Plan Business Features
3.) Build the Quality Matrix
4.) Calculate the importance rating
	
## [[CUSTOMER REQUIREMENTS]] ![[cust_req.png]]

	The example customer reqs can be divides into 2 broad categories(1-5):
		1.) Forecasting
			- Demand Forecast 3 week, 3 month and 6 month >~75%
			- Demand Forecast with short term updates
			
		2.) Infrastructure
			- Easy upload of relevant documents
			- view forecasts with analysis and loss metrics
			- Optimal Model/Data Selection
			- Model results approval and sharing
		Assign weighting to customer requirements
		
## [[Business Features]] ![[business features.png]]
1.) Filling in the [[Business Features]]
	
		In order to fulfill the customer requirements, the business solutions must fulfill all the customer needs. Map out the business features:
		1.) Functionalize Model Training
			- req: forecasting
		2.) Functionalize model testing & selection
		3.) Hyperparameter tuning
		4.) Time series processing and classification
		5.) Feature engineering and management
		6.) create universal forecasting environment
		7.) Data Storage
		8.) vm and server configuration for testing and deployment
		9.) data processing flow and functionalization
		10.) API backend managements for forecasting features
		11.) Visualization and planner UI with collaboration and approval features
	
2.) Filling in the feature  - (optional)
	- Correlation Matrix Legend ![[correlation legend.png]]
	- Correlation Matrix ![[feature correlation.png]]
	
		The goal of the correlation matrix is to illustrate the relationship that features may have with each other. This is less of an issue with software arguments and can typically can be see in physical products. For example, when designing a car,the customer may want a new material in the chassis to make the car look better;however, this may be at the expense of another feature such as speed due to the increased weight of the new material. These features would be negatively correlated.
	
	
	
## Building the [[Quality Matrix]]
1.) Studying the Legend ![[relationship legend.png]]
	
	This legend helps assign the relationship strength of a business feature to solve a customer requirement.
2.) Filling out the matrix ![[Matrix.png]]
	
	Fill out the matrix for each business feature and judge the degree to which the business feature meets the customer requirements
	
## Calculating the importance rating ![[HoQ-importancerating.png]]
	
	1.) multiply the relationship matrix values with the customer importance rating.
	2.) sum each column to figure out the importance rating of each feature.
	3.) calculate the percent importance each feature is assigned by dividing each column by total importance.
	
	
	
## The Full [[House of Quality]]
	The house of quality allows you to get a robust understanding of the business features build out and how to prioritize them. It also helps to underestand how certain features interact with each other.
	
	
	
Now that the House of Quality is built, we can focus on our expanding our business features into more digestable [[System of Quality]]

	


	

	
			