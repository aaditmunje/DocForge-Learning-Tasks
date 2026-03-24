Task 2a was about implementing a linear regression model. Like always, we first imported the notebook and datasets needed into Kaggle. Then, with import os and os.listdir(‘/Kaggle/input’), we traced the location of the file to finally read the CSV file and print the plot using df.head()

This task taught me about standardization ie bringing the data to a relevant scale so that it is easier for the machine to predict values. It improves the stability and convergence of gradient descent. We did it using z = (x - μ)/ σ

This helped me understand how machine learning models work internally, rather than just using built-in libraries.
One thing I learnt specifically through this task was how gradient descent works. I implemented forward propagation to make predictions, computed the cost using Mean Squared Error (MSE), and used backward propagation to update slope and intercept.

An error I faced was that I was getting NAN for almost every output, so with the help of chatGpt I learnt how to drop the data.

I am currently learning classes as part of my PSC, but the code used in this was much more complex. I did as much as I cld using my own understanding and learnt the rest with the help of ai.


Task 2b was about implementing a logistic regression model. Logistic Regression is a supervised machine learning algorithm used for classification problems. Unlike linear regression, which predicts continuous values, it predicts the probability that an input belongs to a specific class.

I learnt the differences between linear and logistic regression, as well as the 3 types of logistic reg. Instead of the line of best fit, we have a sigmoid function, which gives a probability between 0 and 1. I learned that Logistic Regression uses the sigmoid function to convert linear outputs into probabilities between 0 and 1. These probabilities are then converted into class labels using a threshold (typically 0.5).


Task 2c helped with experimenting with linear regression. After importing the notebook and getting the table we were tasked with taking any 3 columns and training our own model. As much as ive understood there are like a few steps that need to be followed in order to do the task-
Load dataset – Define X and y – Train_Test Split - Use your Linear Regression class – Predict – Evaluate (MSE)

One completely new thing I learnt in 2c was the importance of the relationship between features. I also learned about multicollinearity, where one feature is a scalar multiple of another. This can cause instability in the model and make it difficult to interpret coefficients.


An interesting learning was using log instead of MSE/RMSE. 

I also learnt that in classification tasks, it's crucial to evaluate the performance of your model using classification metrics like accuracy, precision, recall, and F1 score.

The code was slightly simpler as compared to the a) task, as in most places we had to return the metric formula in the designated class function.
