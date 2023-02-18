# final_advanced_programming
Below is what I did. The full version of report with figures is in moodle.

Link Youtube
https://youtu.be/q5wAYwMfvCE

Idea Proposal

Problem or idea description
Used car price prediction. In this project the price of used cars will be estimated according to the features and condition of the car.
Background information on the problem or idea
It is common to resell your car to another person, and buy used car by someone else. This project aims to facilitate cars trade and help people, who lack experience of determining used cars’ worth.
Available solutions with links
There are available solutions in github with 16 public repositories. The link is: https://github.com/topics/used-cars-price-prediction . Mostly, the problem is written in Python and has regression algorithms.
How to get the data?
I am planning to use Kaggle.com to obtain needed datasets of used cars.
Brief description of your solution
The solution of the problem will be gotten by obtaining data of used cars, using linear regression and predicting the prices.
Tech stack that will be used
Python will be used for this problem.

Process of work

Dataset and information about it
I used dataset from Kaggle.com (https://www.kaggle.com/datasets/nehalbirla/vehicle- dataset-from-cardekho?select=car+data.csv). I obtained information about it:
 It has 301 rows and 9 columns
 There are no null values. All data is present.
 Types of fuels: petrol, diesel, CNG
 Types of sellers: dealer, individual
 Types of transmissions: manual, automatic
 Number of owners(how many people owned the car): 0, 1, 3

Manipulations with dataset
I added new column “Age” to the table. On the Figure 4 first five rows of changed table can be seen.
Figure 4. The screenshot from Google Colab
Also, categorical data was encoded, because numbers are more understandable for model training. For example, in the new table, categorical data of the seller type “Dealer” and “Individual” are 0 and 1 respectively.

 Figure 5. The screenshot from Google Colab
Model training. Visualization
 Lasso Regression is used for model training. It is an extension of linear regression that
 adds a regularization penalty to the loss function during training. R squared error during
 training is 0.8427865885661434 and during testing is 0.8709151375567289. Visualization of
 it is provided on the plots.

Conclusion
Model training for “Used cars price prediction” is done. To achieve it, dependencies for working with datasets were imported, dataset of cars was loaded, and Lasso regression model is used.

Literature review
1. https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from- cardekho?select=car+data.csv
2. https://youtu.be/L3OtLaCbJC8
3. https://youtu.be/RdPhkPDFabM
4. https://vitalflux.com/lasso-ridge-regression-explained-with-python-example/
     
