# DataA-VBanking
Data Analysis visualization in Banking

The purpose of this lab is to master visual data analysis in banking for machine learning models.

During the work, the task of a preliminary analysis of a positive response (term deposit) to direct calls from the bank is solved. 

In essence, the task is the matter of bank scoring, i.e. according to the characteristics of clients (potential clients), their behavior is predicted (loan default, a wish to open a deposit, etc.).

Conclusions:

There are neither any data missing, nor explicit outliers that should be cut. But we can omit housing, loan and day_of_week features in the next steps.

The euribor3m and nr.employed features strongly correlate with emp.var.rate. Let me remind you that emp.var.rate - Employment Variation Rate is a quarterly indicator, euribor3m - euribor 3 month rate is a day indicator, and nr.employed - number of employees is a quarterly indicator. The correlation of the employment change with the number of employed issues itself is obvious, but its correlation with EURIBOR (Euro Interbank Offered Rate, the European interbank offer rate) is interesting. This indicator is based on the average interbank interest rates in Eurozone. It also has a positive effect since the higher the interest rate is, the more willingly customers will spend their money on financial tools.

Therefore, if banks want to improve their lead generation, what they should do is to improve the quality of phone conversations and run their campaigns when interest rates are high and the macroeconomic environment is stable.
