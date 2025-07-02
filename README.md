Task 3 :  Sales Prediction Using Python

This project predicts future sales based on key business factors such as advertising spend, target segment, and platform. It uses a simple Linear Regression model and basic Python libraries, making it ideal for beginners exploring data science and machine learning.

Sales prediction is a crucial task for businesses aiming to make informed decisions regarding production, marketing, and resource allocation. Predicting future sales allows companies to strategize and optimize their efforts across different platforms and target audiences. This project focuses on building a simple yet effective machine learning model to predict future sales based on key factors such as:
* Advertising Spend: The amount of money invested in advertisements.
* Platform: The medium used for advertising (e.g., TV, Social Media, YouTube).
* Target Segment: The customer group targeted by the advertisement (e.g., Teens, Adults, Seniors).
_____________________________________________________________________________________________________________________________________________________________________________________________________________
**Objective**

* The primary objective of this project is to:
* Forecast future sales based on advertising-related parameters.
* Analyze how changes in advertising spend and strategy influence sales outcomes.
* Provide a basic but functional model for business decision-making using regression.
_____________________________________________________________________________________________________________________________________________________________________________________________________________
**Methodology**

* Data Collection:
  The dataset contains historical advertising records with columns such as Advertising Spend, Platform, Target Segment, and Sales.
* Data Preprocessing:
  Missing values are handled.
  Categorical variables like Platform and Target Segment are converted to numeric codes using label encoding.
  Data is prepared for training by selecting appropriate features and the target column.
* Model Building:
  The dataset is split into training and testing sets.
  A Linear Regression model is used because it’s simple, interpretable, and suitable for numeric prediction tasks.
  The model is trained using the training data and tested on unseen data.
* Evaluation:
  The model’s performance is evaluated using Mean Squared Error (MSE).
  Actual vs predicted sales values are displayed to measure accuracy.
_____________________________________________________________________________________________________________________________________________________________________________________________________________
**Outcome**

* Predicted sales figures for given advertising conditions.
* Insights into how platforms and target segments impact sales.
* A trained model that can be reused for predicting sales on new data.
_____________________________________________________________________________________________________________________________________________________________________________________________________________
**Conclusion**

This project demonstrates how a basic machine learning model can be effectively used to forecast sales by analyzing historical advertising data. While simple, the model provides valuable insights that can guide real-world business marketing strategies. It also serves as an excellent beginner-friendly introduction to data science and regression modeling using Python.
