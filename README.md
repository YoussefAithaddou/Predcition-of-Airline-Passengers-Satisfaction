# Predcition-of-Airline-Passengers'-Satisfaction
This project aims to compare different classification models (Logistic regression, Decision tree, and SVM) to predict airline customers' satisfaction.


# Resources Used
* Python Version: 3.7
* Packages: pandas, numpy, sklearn, matplotlib, seaborn, selenium.
* ChromeDriver 95.0.4638.10 [download](https://chromedriver.chromium.org/downloads).
# Data used
* Airlines Customer satisfaction [download](https://www.kaggle.com/kerneler/starter-airlines-customer-satisfaction-a981ed4d-6/data).
* This data shows whether a customer is satisfied with the airlines or not based on different 9 attributes:
  1. Gender
  2. Customer Type
  3. Age
  4. Type of Travel
  5. Class
  6. Flight Distance
  7. Seat comfort
  8. Departure/Arrival time convenient
  9. Food and drinks

# Data preparation
* Removed missing values.
* Sampled data for analysis and visualization.
* Visualised correlation between attributes:
![image 1](https://github.com/YoussefAithaddou/Predcition-of-Airline-Passengers-Satisfaction/blob/main/Correlation%20Matrix.png)
* SVM is a slow algorithm, thus I used a sample of 5000 rows from the original data as opposed to 100.000 samples used for the logistic regression and Decison tree model.
# Classifcation models:
###### Logistic regression:
* Mean Absolute Error: 0.161
* Accuracy: 0.84
###### Decision tree:
* Mean Absolute Error: 0.062
* Accuracy: 0.94
###### Support vector machine:
* Mean Absolute Error: 0.092
* Accuracy: 0.91

![image 2](https://github.com/YoussefAithaddou/Predcition-of-Airline-Passengers-Satisfaction/blob/main/Confusion%20matrix.png)
