# Project : Feature Model Tuning

## Content 

 - Data Description	
 - Domain
 - Context
 - Attribute Information
 - Learning Outcomes
 - Objective
 - Steps and tasks
 
	
- ### Data Description: 	

	The data contains features extracted from the silhouette of vehicles in different angles. Four "Corgie" model vehicles were used for the experiment: a double
    decker bus, Cheverolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of vehicles was chosen with the expectation that the bus, van 
	and either one of the cars would be readily distinguishable, but it would be more difficult to distinguish between the cars.

	
- ### Domain:

    Cement manufacturing
	

- ### Context:

	Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients.
    These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate.
	

- ### Attribute Information:

	- Cement : measured in kg in a m3 mixture
	- Blast : measured in kg in a m3 mixture
	- Fly ash : measured in kg in a m3 mixture
	- Water : measured in kg in a m3 mixture
	- Superplasticizer : measured in kg in a m3 mixture
	- Coarse Aggregate : measured in kg in a m3 mixture
	- Fine Aggregate : measured in kg in a m3 mixture
	- Age : day (1~365)
	- Concrete compressive strength measured in MPa

	  
- ### Learning Outcomes:

	- Exploratory Data Analysis
	- Building ML models for regression
	- Hyper parameter tuning
	

- ### Objective:

    Modeling of strength of high performance concrete using Machine Learning.

	  
- ### Steps and tasks:

	1. Deliverable-1 (Exploratory data quality report reflecting the following)

		a. Univariate analysis 
		
			i. Univariate analysis – data types and description of the independent attributes which should include (name, meaning, range of values observed,
			central values (mean and median), standard deviation and quartiles, analysis of the body of distributions / tails, missing values, outliers
			
		b. Multivariate analysis
			i. Bi-variate analysis between the predictor variables and between the predictor variables and target column.
			   Comment on your findings in terms of their relationship and degree of relation if any. Presence of leverage points.
               Visualize the analysis using boxplots and pair plots,histograms or density curves. Select the most appropriate attributes
			   
		c. Pick one strategy to address the presence outliers and missing values and perform necessary imputation 
		
	2. Deliverable-2 (Feature Engineering techniques)

		a. Identify opportunities (if any) to create a composite feature, drop a feature etc.
		
		b. Decide on complexity of the model, should it be simple linear model in terms of parameters or would a quadratic or higher degree help.
		
		c. Explore for gaussians. If data is likely to be a mix of gaussians, explore individual clusters and present your findings in terms of the
           independent attributes and their suitability to predict strength 

	3. Deliverable-3 (create the model ) 
	
		a. Obtain feature importance for the individual features and present your findings
		
	4. Deliverable-4 (Tuning the model) 
	
		a. Algorithms that you think will be suitable for this project 
		
		b. Techniques employed to squeeze that extra performance out of the model without making it overfit or underfit
		
		c. Model performance range at 95% confidence level 