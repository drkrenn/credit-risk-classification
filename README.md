# credit-risk-classification
Module 20

**Analysis Overview ** The purpose of the analysis to create and evaluate a model capable of predicting whether a loan application should be accepted or rejected. The model uses existing data showing what contributed to the acceptance or rejection of loans previously. A model is then created that can predict uwhether future loans should be acceptable or rejectable in the future. 

**Results ** The following shows the results for each of the two models generated:
_Measure			            Real Data Model	  Simulated Model_
Accuracy			              0.99			      0.99
Precision- Healthy Loan			1.00			      1.00
Precision-Risky Loan			  0.85			      0.84
Recall- Healthy Loan			  0.99		      	0.99
Recall- Risky Loan		     	0.91			      0.99
f1- Healthy Loan		      	1.00		      	1.00
f1- Risky Loan		        	0.88			      0.91


**Summary ** Two different models were generated. One uses real data. The other uses similated/bootstrapped data. Both models show adequate levels of fit. However, the collective indices suggest that the model using the simulated data had slightly better fit. As such, either model could be used. But the latter would be a stronger option. 


**File Location ** The key file for this assignment credit_risk_classification.ipynb can be found in the starter_code folder of the repository.


**Syntax Sources ** Learning assistants helped me figure out the syntax to create the resampled data. All of the remaining code was self-generated or was copied and altered from class material.
