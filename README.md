## Auto_MPG

**Domain**<br/>
This problem is drawn from the analysis of the specifications of various automobile models. This dataset have been widely used in the research of machine learning such as doing classifications with “model trees”. (Wang, Y & Witten, H, 1997)

**Problem Statement**<br/>
Given a dataset which contains the miles per gallon (mpg), cylinders, displacement, horsepower, weight, acceleration, model year, origin and car name. We will use supervised learning to develop a regression model that can predict a car’s acceleration based on the number of cylinders, displacement and weight of the car. While not always true, a car with a higher number of cylinders and displacement while having a lower weight usually means it has a faster acceleration, based on the equation Acceleration=Force/Mass. There are other factors that could increase the acceleration of a car, but we would like to see if in general the equation holds true when applied to a dataset collected from a real world scenario. 

**Data Sets and Inputs**<br/>
The dataset to be examined is the Auto MPG dataset on the UCI Machine Learning Repository. We will not be using the original dataset as 8 of the original instances as they have missing values for mpg. The dataset consist of 398 rows and 9 columns (including the class attribute of the car models).
The columns attributes are “mpg”, “cylinders”, “displacement”, “horsepower”, “weight”, “acceleration”, “model year”, “origin”, “car name (brand and model)”. However, in this study, we will just be studying the relationship between weight, displacement, number of cylinders in relations to the acceleration.
The size of the entire dataset is 30KB. More descriptions and summaries of the dataset can be found on the accompanying notebook.

**Solution Statement**<br/>
A solution to this problem will be using several linear regression models.

**Benchmark Model**<br/>
Given that we seek a regression model a good naive benchmark would be to use the mean of the acceleration from the dataset.

**Evaluation Metrics**<br/>
We will use the R-squared metric and Mean Absolute Error to measure the success of our model.

**Resources**<br/>
Wang, Y, Witten, H. 1997. Inducing Model Trees for Continuous Classes. University of Waikato.
https://www.cs.waikato.ac.nz/~ml/publications/1997/Wang-Witten-Induct.pdf
