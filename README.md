# Predicting Taxi Gratuities in New York City

# Overview
The goal of this project is to create a build a machine learning model to predict high rider gratuity or not. This project utilized yellow taxi trips taken in New York City during 2017. The final Random Forest model performed with an F1 score of 0.756 and accuracy of 71.6% determining what features are most important in separating low tippers from high tippers. Based on the model VendorID, duration and distance were most influential in determining a generous tipper (>=20%) vs non-generous tipper (<20%).

# Business Understanding
According to salary.com the average salary for a New York Taxi Driver is around $45,000. This salary is significantly low compared to a median rent value of aprrox. $6,400 per month. It is important to undertand what factors encourage riders to leave tips in order to help drivers obtain a liveale wage.

# Data Understanding
The dataset is from NYC.gov. The data consisted of approximately 408K unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll, tip and fare amounts, payment type, pickup and drop off times and locations.

# Modelling and Evaluation
A random forest model comprising of 300 decision trees was used to determine feature importance in who would tip generously or not. The vendorID, trip duration, trip distance were the top 3 most important factors in determining a generous tipper and non-generous tipper. The overall model performed with 71.6% accuracy and F1 score of 0.756.

# Conclusion
The random forest model produced decent results. However, the model efficiency could be improved by adding more information on a customer's past tipping behavior and segregating tips with distance would benefit the stakeholder address their business problem.
