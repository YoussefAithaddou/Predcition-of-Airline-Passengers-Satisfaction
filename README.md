# Predcition-of-Airline-Passengers-Satisfaction
This projects aim to compare different classification models (Logistic regression, Decision tree and SVM) to predict airline customers' satisfaction.

* Scraped over 500 pages of reviews and ratings from RotenTomatoes.com for the movie Mortal Kombat 2021 using python and selenium.
* Cleaned and converted data into a matrix of token counts with the help of sklearn's CountVectorizer.
* Optimized Naive-Bayes multiclass classifier using GridsearchCV to choose the optimal parameters.
* Classified data and predicted the movie ratings based on the written reviews.

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
* We visualize the correlation between attributes:
![image 1](https://github.com/YoussefAithaddou/Predcition-of-Airline-Passengers-Satisfaction/blob/main/Correlation%20Matrix.png)
## The data extraction process gives the following results:
  1. Reviews: written critic of users.


