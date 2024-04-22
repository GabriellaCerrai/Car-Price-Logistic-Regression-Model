This project uses data and some code from 'The Complete Data Science Bootcamp' on Udemy (https://www.udemy.com/).

This is a practical example in how to preproccess data to create a predictive linear model. 

The code to create the model includes scaling inputs. Scaling is used to ensure that all input variables contribute equally to the output. 
Source on why scaling and standardization is important: 
https://analyticsindiamag.com/why-data-scaling-is-important-in-machine-learning-how-to-effectively-do-it/ 

The first part of this repository is code for preprocessing the data: exploring variables of interest, 
removing null values from the data set, extreme values in the data when plotting the PDFs. 

This is a Logistic Regression problem. One can use matplotlib to plot the variables of interest against 'Price' and 
then again against the logarithm of 'Price' to see why this transformation was made. 

The second part is code for scaling, fitting a linear model, splitting the data and testing the model for predictive analysis purposes. 

An important note: 
Since the data has undergone a log transformation, one must transform the data back by using the exponential function 
i.e. np.exp()

