This file was made to save the summarized contents from https://ourcodingclub.github.io/tutorials/mixed-models/.

1. What is mixed effects modelling and why does it matter? </br>
Mixed models were developed, to deal with such messy data and to allow us to use all our data, even when we have low sample sizes, structured data and many covariates to fit.
Mixed models allow us to save degrees of freedom compared to running standard linear models.

2. Explore the data </br>
The response variable is the focus of a question in a study or experiment. An explanatory variable is one that explains changes in that variable. It can be anything that might affect the response variable.
It is good practice to standardise your explanatory variables before proceeding so that they have a mean of zero (“centering”) and standard deviation of one (“scaling”). It ensures that the estimated coefficients are all on the same scale, making it easier to compare effect sizes. You can use scale() to do that:
scale() centers the data (the column mean is subtracted from the values in the column) and then scales it (the centered column values are divided by the column’s standard deviation).

3. Fit all data in one analysis

4. Run multiple analyses

5. Modify the current model

6. Mixed effects models

7. THE END
