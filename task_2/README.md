Task 2a was about implementing a linear regression model. Like always, we first imported the notebook and datasets needed into Kaggle. Then, with import os and os.listdir(‘/Kaggle/input’), we traced the location of the file to finally read the CSV file and print the plot using df.head()

This task taught me about standardization ie bringing the data to a relevant scale so that it is easier for the machine to predict values. It improves the stability and convergence of gradient descent. We did it using z = (x - μ)/ σ

This helped me understand the internal working of machine learning models instead of just using built-in libraries.
One thing I learnt specifically through this task was how gradient descent works. I implemented forward propagation to make predictions, computed the cost using Mean Squared Error (MSE), and used backward propagation to update slope and intercept.

An error I faced was that I was getting NAN for almost every output so with the help of chatGpt I learnt how to drop the data.

I am currently learning classes as part of my PSC, but the code used in this was much more complex. I did as much as I cld using my own understanding and learnt the rest with the help of ai.
