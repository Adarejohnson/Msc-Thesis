# Msc-Thesis
## Empirical Evaluation of Predicting Carbon Emissions in Europe: A Comparative Analysis and Evaluation
### Results
This section presents the prediction result every year from years 1 to 5. Next, RF is evaluated against all other models using the R2 score and MSE metrics. Finally, the prediction accuracy is observed as it varies from year to year.
#### Year 1
In year 1, the RF model achieved the highest R2 score of 0.99 and the lowest MSE value of 0.01, indicating that it had the best performance predicting carbon emissions for that year. DT and LR models also performed well, with an R2 score of 0.98 and an MSE value of 0.02 and 0.01, respectively. The deep learning models all had R2 scores below 0.89, and their MSE values were higher than those of the random forest, decision tree and linear regression models. 
Figure 4 8 First-year MSE chart
#### Year 2
The RF model continued to perform best in predicting carbon emissions in year 2, as evidenced by its highest R2 score of 0.99 and lowest MSE value of 0.01. The DT model likewise did well, scoring 0.98 on the R2 scale and 0.02 on the MSE scale. The R2 scores of the deep learning models were all lower than 0.88, and their MSE values were higher than those of the LR, RF and DT models. The LSTM model obtained the greatest MSE value (0.1992) and the lowest R2 score (0.7452). 
Figure 4 9 MSE of models for year two prediction
#### Year 3
In year 3, the RF model performed the best, achieving an R2 score of 0.98 and maintaining the MSE value of 0.01. The baseline models DT and LR had R2 scores of 0.97 and 0.95, respectively. Their MSE values are 0.02 and 0.04. On the other hand, the deep learning models all had R2 scores of 0.86, and their MSE values were higher than those of the baseline and the proposed models. The LSTM model consistently had the lowest R2 score of 0.7364 and the highest MSE value of 0.213.

Figure 4 10 MSE of models for year three prediction
#### Year 4
In year 4, the RF model continued to have the highest performance in predicting carbon emissions, earning a maximum R2 score of 0.98 and the lowest MSE value of 0.02. With an R2 score of 0.97 and an MSE value of 0,3, the DT model performance closely tracks the RF. 
Figure 4 11 MSE of models for year four prediction
#### Year 5
In year 5, the last year of the prediction, the RF model again achieved a high R2 score of 0.97 and the lowest MSE value of 0.03 compared to all other models, indicating that it had the best performance in predicting carbon emissions for the final year. The DT model had an R2 score of 0.96 and an MSE value of 0.04. The deep learning models all had R2 scores below the LR, which had 0.90, and their MSE values were higher than those of the baseline and proposed models. The NN model had the lowest R2 score of 0.7093 and the highest MSE value of 0.2476. 
Figure 4 12 MSE of models for year five prediction
#### Summary
The RF model outperformed all other models in predicting carbon emissions for the next five years. In addition, the model achieved high accuracy and low error rates, making it suitable for predicting carbon emissions in the future. The results of this study can help develop policies and strategies to reduce carbon emissions and mitigate the effects of climate change. 
 
 ![MSE of models for all-year prediction ](MSE%20of%20models%20for%20all-year%20prediction.png)
It was found that the model's predictions for year one were more accurate than those for year five after examining models that predicted carbon emissions over five years using the R2 score and MSE. This shows the model's predictive performance increases as the forecasted time frames shorten.
 
![MSE performance for all year ](MSE%20performance%20for%20all%20year.png)
 
![R2score for all-year prediction](R2score%20for%20all-year%20prediction.png)
