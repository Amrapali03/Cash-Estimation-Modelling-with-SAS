# Cash-Estimation-Modelling-with-SAS
Cash Estimation Modelling

Introduction: Understanding the pivotal role of cash holdings in shaping a firm's future performance and market dynamics is crucial in modern financial analysis. Our analysis aims to estimate optimal cash levels for individual firms. Through rigorous statistical modeling, we seek to ascertain whether companies hold surplus or inadequate cash compared to their estimated targets.
![image](https://github.com/Amrapali03/Cash-Estimation-Modelling-with-SAS/assets/114306627/f2ec8cf0-7b99-404b-a6e8-01e1bc601139)


## Dataset:
The data used for our analysis is sourced from the WRDS portal, specifically the Compustat - Fundamentals Annual section for the North America region, covering the period from 1960 to 2022. 

## Source:
https://wrds-www.wharton.upenn.edu/pages/get-data/compustat-capital-iq-standard-poors/compustat/north-america-daily/fundamentals-annual/



## Proposed Cash Estimation Models
Model 1 for cash estimation:

Cash = Intercept + Firm size + NetWorkingCapital + Capital Expenditures + IndustrySigma + R&D +Dividend Dummy + SalesGrowth + CashfromOperations + FirmAge + TaxBurdenonForeignIncome+ YearDummies +IndustryDummies + Managerial Ability + Error


Model 2  for cash estimation:

Cash = Intercept + Firm size + NetWorkingCapital + Capital Expenditures + IndustrySigma + R&D +Dividend Dummy + SalesGrowth + CashfromOperations + FirmAge + TaxBurdenonForeignIncome+ YearDummies +IndustryDummies + Managerial Ability + Leverage + MarketToBook + InterestRates + Error

## Data Overview and Data Processing
![image](https://github.com/Amrapali03/Cash-Estimation-Modelling-with-SAS/assets/114306627/7950d84f-fde5-48db-bfc6-2a8f5338b43f)


## Correlation
From the results, we know the strength and magnitude of the relation between Cash and other variables. Key relationships are as below:
Cash from Operations: A strong negative correlation (-0.62) suggests a robust negative linear relationship, indicating that as cash from operations increases, cash estimates tend to decrease.
Research & Development: A moderate positive correlation (0.359) implies that there is a moderate positive linear relationship between research and development and cash estimates.
Leverage: A moderate positive correlation (0.349) suggests a moderate positive linear relationship between leverage and cash estimates.
Net Working Capital: A negative correlation (-0.45) indicates a moderate negative linear relationship, suggesting that as net working capital increases, cash estimates tend to decrease.

## Regression Results
![image](https://github.com/Amrapali03/Cash-Estimation-Modelling-with-SAS/assets/114306627/ea17d9be-06a6-489a-869c-6a7f78abd70e)

Model Significance:
The overall model fit is assessed using the R-squared value, which is 0.4682. This indicates that approximately 46.82% of the variance in cash estimation can be explained by the variables included in the model.
The F-statistic for the model is 1017.30 with a p-value < .0001, signifying that the model is statistically significant in explaining the variance in cash estimation. This indicates that the joint effect of all the predictors in the model is statistically significant in predicting cash level.

Model 2:
We expanded our analysis by incorporating additional factors including Leverage, Market to book, and Interest rates to consider the factors that were previously overlooked. The inclusion of these variables potentially enhances the explanatory power of the model, offering a more realistic representation of the complexities involved in cash estimation. We also see consistent results in terms of positive and negative signs for all the variables in both models.



## Recommendations
![image](https://github.com/Amrapali03/Cash-Estimation-Modelling-with-SAS/assets/114306627/8a1f7558-30b4-4e5a-b5b1-8e5cade46b49)

