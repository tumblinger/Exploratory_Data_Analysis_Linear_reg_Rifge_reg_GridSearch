# Exploratory Data Analysis
## Linear regression, Ridge regression, GridSearch
![pict](https://user-images.githubusercontent.com/77502878/228066923-48e01f49-c9cd-4a42-adc2-d58dbceedfbf.JPG)
### The data consists of information about various car models, including their make, model, volume, weight, and CO2 emissions. 
#### Based on the use of linear regression, ridge regression, and grid search methods on this dataset, the following summary can be written:

#### Linear regression: The linear regression model was used to analyze the relationship between the car features (volume and weight) and CO2 emissions. The model showed a moderate positive correlation between volume and CO2 emissions, and a strong positive correlation between weight and CO2 emissions. However, the model did not perform well in terms of accuracy and had a high variance.

#### Ridge regression: The ridge regression model was used to address the issue of high variance in the linear regression model. By introducing a regularization term, the model was able to reduce the variance and improve the accuracy. The optimal regularization parameter was found using grid search.

#### Grid search: Grid search was used to tune the hyperparameters of the ridge regression model, such as the regularization parameter. By performing a systematic search over a range of values for the hyperparameters, the optimal combination was identified, leading to improved model performance.

### In summary, the use of ridge regression and grid search methods led to a more accurate and stable model for predicting CO2 emissions based on the car features of volume and weight. The analysis showed that weight has a stronger influence on CO2 emissions than volume. The model can be used to inform policy decisions related to reducing carbon emissions from vehicles.
