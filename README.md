# Ad_Click-Prediction-Using-Logistic-Regression

### Project objective:

The primary goal of this project is to build a predictive model that determines whether a user is likely to purchase an item after clicking on an advertisement. By analyzing demographic data, the model aims to provide insights that empower the business to optimize its advertising strategies and improve sales outcomes.

#### Dataset:

The dataset used for this project, sourced from [Kaggle](https://www.kaggle.com/jahnveenarang/cvdcvd-vd), contains demographic information of users, including:
- [x] User ID: Unique identifier for each user.
- [x] Gender: Binary variable indicating whether the user is female.
- [x] Age: User’s age in years.
- [x] Estimated Salary: Estimated annual income of the user.
- [x] Purchased: Binary variable indicating whether the user purchased a product after clicking on an ad.

#### Methodology:

#### Data Exploration and Visualization
   - [x] An initial exploration was conducted to understand the dataset's structure, types, and distribution of variables.
   - [x] Visualization: A histogram was used to examine the distribution of age across genders, revealing a balanced dataset with most users aged between 20 and 50 years.

#### Data Preprocessing
   - [x] Splitting the Data: The dataset was split into training (80%) and testing (20%) sets to evaluate the model's performance on unseen data.
   - [x] Feature Scaling: StandardScaler was used to normalize the features, ensuring that variables with different units do not skew the model's performance.

#### Model Building
   - [x] Logistic Regression: A logistic regression model was developed using both `sklearn` and `statsmodels` libraries to predict the likelihood of a user purchasing after clicking on an ad.
   - [x] Training and Testing: The model was trained on the training set and evaluated on the test set, with accuracy scores calculated to assess performance.

#### Model Evaluation
   - [x] Accuracy: The model’s accuracy on both training and test sets was computed.
   - [x] Confusion Matrix: A confusion matrix was plotted to visualize the model’s performance, showing the distribution of true positives, true negatives, false positives, and false negatives.
   - [x] Odds Ratios: Using `statsmodels`, the coefficients were interpreted as odds ratios, providing insights into the impact of each feature on the likelihood of purchase.

#### Insights
   - [x] Gender Influence: The analysis showed that gender significantly influences the likelihood of making a purchase, with males being less likely to purchase than females.
   - [x] Statistical Significance: The p-values from `statsmodels` indicated that gender is a statistically significant predictor of purchase behavior, while age and estimated salary were less so.

#### Conclusion
- This project successfully developed a logistic regression model to predict whether a user will purchase after clicking on an advertisement. The analysis provided valuable insights into the demographic factors influencing purchase decisions, particularly the role of gender. The model and findings can be used to optimize ad targeting strategies and improve overall sales performance.

#### Future Work
- [x] Feature Engineering: Explore additional features or transformations to enhance model accuracy.
- [x] Model Comparison: Compare logistic regression with other classification models such as Random Forest or SVM.
- [x] Hyperparameter Tuning: Optimize model parameters to improve performance.
