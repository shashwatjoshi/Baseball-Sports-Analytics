# Baseball-Sports-Analytics
Basketball Team Prediction To Make It To Playoffs: Dealt with the data collected from the trusted website of the detailed summary of the players and their valuation on various parameters throughout previous seasons and predicting the ability of the team to make it to playoffs, and if so what is the average point difference needed to score consistently. Prediction accuracy had errors ranging from 10-15% over test set. 

This project comprises of sports analytics and the power of analytics which helps us in making a model so strong.
The dataset contains 15 variables.
The dependent variable which i aimed to predict is the number of “wins”.
 Creating a new variable called RD(runs difference ) and then checking the linearity of this new variable with the wins with the plot function. We find out there is a strong linear relationship which we can exploit for our regression model.
First constructing a regression model for Wins and from the linear regression equation built can be used to calculate the value of ‘How much the runs difference should be?’
The second regression model helps to answer the question that ‘How does a team score more runs?’. It uses the other variables of On base percentage(that how much time the player take to reach on to the base) and On sluggish percentage to determine the RunsReg model. Similarly calculating the runs allowed with variable having prefix of “O” i.e. opponent’s on base percentage and opponent’s on sluggish percentage.
The inferences from this project can be summed as 
•	After constructing the model with different variables we can check that if the variables are significant enough in our model i.e. it do they really affect he model’s prediction or not.













