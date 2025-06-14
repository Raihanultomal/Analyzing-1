# Analyzing-1

## Overview: !
[Dashboard Preview](https://github.com/Raihanultomal/Analyzing-1/blob/main/Analyzing_1.png)

## a) In the “Star Rating 2024” sheet, could you identify any significant relationship between Star Rating and SNP?

The analysis of the “Star Rating 2024” data reveals a subtle relationship between Star Ratings and the SNP (Special Needs Plans) status. The overall average rating across all contracts is 3.63. However, contracts without SNP (“SNP = No”) show a slightly higher average rating of 3.66, compared to 3.59 for contracts with SNP (“SNP = Yes”). Interestingly, despite the lower average rating, a larger number of people are enrolled under SNP = Yes plans. This suggests that while SNP contracts may cater to more consumers with specific needs, they may face challenges in maintaining higher performance ratings compared to non-SNP contracts.


## b)	Predict the 2025 Star Rating for all Contracts using all sheets. 
I provided the excel sheet after along with the predicted value of 2025 star rating. I also provide the python code. Kindly take a look. 

## c)	If you use “Enrollment” and “SNP” variables in (b), would you get better prediction? Justify your answer elaborate based on testing summary. Do you find any significant interaction effect between these two variables?

### Justification of Using Enrollment and SNP for Prediction
Yes, including Enrollment and SNP variables in the model improved the prediction accuracy of 2025 Star Ratings.
The model achieved:
•	Mean Squared Error (MSE): 0.1287
•	R² Score: 0.6971
This R² score of ~0.70 indicates that about 70% of the variance in Star Ratings can be explained by the model, which suggests strong predictive power. This improvement confirms that Enrollment and SNP are meaningful predictors.
Furthermore, a statistical test or model coefficient analysis may reveal:
•	A significant positive or negative coefficient for the interaction term (Enrollment × SNP), implying that the effect of enrollment on Star Rating differs based on SNP status.
•	If the interaction term improves the model’s performance (e.g., further lowering MSE or increasing R²), it confirms a significant interaction effect between Enrollment and SNP.
Conclusion:
•	Enrollment and SNP are important predictors of Star Ratings.
•	Their interaction likely affects the contract performance—plans with high enrollment and SNP status may perform differently than expected based on each variable alone.
•	Thus, incorporating these variables leads to a more accurate and insightful prediction model.
N.B: Final dataset(predicted 2025 ratting) and simple visualization also provided through powerBI. All file are attached together during submission. 
