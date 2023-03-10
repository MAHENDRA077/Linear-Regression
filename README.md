# Linear-Regression
step-1: import libaries

step-2: Load data

step-3: Preprocessing

		1. clean.
    
		2. find important independent && dependent variables.
    
		3. deal with missing vakues.
			--check if dependent variables are missing..
      
		4. deal with outliers.
			--remove top 5% or bottom 5%

step-4: Checking the OLS assumptions

		1. linearity: log transdormations
    
            2. no endogenity
    
		3. check for multicollinearity (VIF)
    
		4. no auto correlation
    
		5. Homescadesity

step-5: Data Preparation

    1.create Dummy variables if there are any categorical varibales
    
		2. Scale the data
    
		3. train_test_split

step-6: Model Creation...

		1. create model and fit the data
    
		2. plot y_pred vs y_actual
    
		3. residual plot (y_actual-y_pred).
    
		4. r2 score
    
		5. bias and coefs
		
try to improve varaibles and optimize.
