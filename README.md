<h1><center> <b> Telco Customer Churn Analysis and Churn Prediction </b> </center></h1>
<h4> <center> 6COSC020W Individual Coursework - 2019750 </center> </h4>

<hr>

<h2> <center> <b> Part A - Application Area Review </b> </center> </h2>

<p> <font size='3'>
Researching and analyzing a market with the aim of finding possibilities and evaluating dangers is condisered a "Market Analysis". Analyzing consumer demographics and spending patterns, monitoring competitors and market trends, and gauging the political and economic situation are some examples of what it can entail. Consumer product research, real estate market analysis, stock market analysis, and other applications for market analysis are only a few examples. Business decisions like product development, pricing strategies, and marketing campaigns can be influenced by the market analysis's insights.

Market analysis has seen extensive use of artificial intelligence (AI), which has helped traders and investors by offering insightful analysis and forecasts. Recent research have used AI in a variety of ways for market analysis, including, portfolio optimization, sentiment analysis, risk management, predictive modeling and algorithmic trading. 

One of the most widely used application of artificial intelligence in marketing is predictive analysis and modeling. According to the literature review carried out, it could be said that machine learning, deep learning and neural networks can be used to develop predictive models for stock market prices predicting and forecasting, customer churn prediction, and other market related areas. These models' ability to learn from the past data that were fed during the training process and make predictions according to the slightest shifts in the market which has been found to be more accurate and precise than the traditional or conventional methods that were used earlier.

Sentiment analysis where machine learning algorithms are trained on large amounts of data such as, another well-known application of AI, analyzes a lot of unstructured data, like social media postings, news articles, and other online content, to get insights on market sentiment. It does this by using natural language processing (NLP) techniques. Investors and traders can benefit from this by using it to determine how the general public feels about a certain stock, commodity, or other market-related subject.

Analyzing consumer data is another area of market analysis where AI is frequently applied. Numerous consumer data sources, including social media and e-commerce websites, have been analyzed using AI techniques like machine learning and natural language processing. These research have demonstrated how AI can be used to forecast future sales and determine customer trends and preferences.


Another domain where AI has been used is risk management. Models that can recognize and handle risks in the financial markets have been created using AI approaches including reinforcement learning, deep learning, and genetic algorithms. These models can aid in reducing expected losses and assisting traders and investors in making more informed selections.

 
Another application of AI is in automated trading, where systems that can make buy or sell choices depending on the state of the market have been created using deep reinforcement learning, Q-learning, and evolutionary algorithms. Making quick, informed selections can result in improved returns for traders and investors.

In addition to these particular fields, more general applications of AI are also being utilized to examine market data and create forecasts. For instance, some research has looked into using AI to develop and backtest trading strategies as well as to actually execute transactions based on those methods.
 

In conclusion, the literature review shows that AI has been widely applied within the market analysis domain, providing valuable insights and predictions for investors and traders. Predictive modeling, sentiment analysis, portfolio optimization, risk management, and algo-trading are some of the most popular applications of AI in the field of market analysis. AI has been demonstrated to be a valuable tool for improving the accuracy of predictions, extracting insights from large amounts of unstructured data, and optimizing decision-making in the financial markets.

</font> </p>

<h5> <b> 1. Logistic Regression for Customer Churn Prediction </b> </h5>

<p> <font size='3'> 

Logistic regression is a supervised learning algorithm that is used for classification problems. Modeling the likelihood of a customer leaving can be done using this simple but effective technique. It is a supervised learning algorithm that can be trained on previous customer data and patterns such as customer behavior and usage data such as call duration, customer service interactions, and payment history to find patterns and foretell which customers are most likely to churn, enabling the company to take proactive measures to retain those customers.

Additionally, the logistic regression model will be able to identify the factors that are most important in predicting customer churn and provide insights for the company to take necessary actions. The logistic regression model will estimate the probability of a customer to churn based on the given past data, behaviour and characteristics, and it  classifies the said customer as “churn” or “not churn” based on probability threshold.

Below, said model has been evaluated in terms of data availability, time to setup, time to provide results, output, strengths and weaknesses and data types of the inputs and outputs of the model.

* <b> Data accessibility: </b> Logistic regression performs well with less data, making it more appropriate for datasets with few observations. 

* <b> Time to setup: </b> Compared to gradient boosting and random forests, which can take more time and computational power, logistic regression is easier to set up and train. 

* <b> Time to provide results: </b> Compared to gradient boosting or random forests, which may take longer to train and produce results, logistic regression is computationally less demanding. 

* <b> Output: </b> Because logistic regression is a straightforward and interpretable model, it is simple to comprehend the variables that affect customer churn. The result is a likelihood that a consumer will leave. 
When working with tiny datasets, regularizing logistic regression might be helpful to prevent overfitting.

* <b> Strengths: </b> It is simple to comprehend and implement, has straightforward results to interpret, and can handle both linear and non-linear correlations between variables.

* <b> Weaknesses: </b> Assumes linearity between the independent variables and the log odds of the dependent variable, may not perform well on highly non-linear data.

* <b> Data types (input & output): </b> Requires numerical or data that can be converted to numerical as input, and the result is a probability value that a given input data point belongs to a particular class.

It's crucial to note that, although being faster and using less data, Logistic Regression may not always be as effective as Random Forest or Gradient Boosting and may not be able to capture the non-linear relationship between the independent variables and the dependent variable. A holdout set or cross-validation should be used to assess the model's performance before making a final choice.

</font> </p>

<h5> <b> 2. Random Forests for Customer Churn Prediction </b> </h5>

<p> <font size='3'>

Random forests is an ensemble learning method for classification and regression problems. To increase prediction accuracy, the Random Forest ensemble approach mixes various decision trees. It functions by using random subsets of the data to train numerous decision trees, averaging their forecasts, and then making a final prediction.

The main difference between random forests and gradient boosting is that each tree in RF is constructed individually using a random subsample of the training data, whereas in Gradient Boosting, each tree is constructed using the errors made by the preceding trees. By averaging the forecasts given by all the trees in the ensemble, or by holding a majority vote, the final prediction is determined. For a variety of predictive tasks, including predicting customer turnover, random forests have been demonstrated to be quite effective. Because it is resistant to outliers and noisy data, and because it helps prevent overfitting, it is widely employed. 

Below, said model has been evaluated in terms of data availability, time to setup, time to provide results, output, strengths and weaknesses and data types of the inputs and outputs of the model.

* <b> Data accessibility: </b> Random forests are capable of handling both small and large datasets. In contrast to logistic regression, it is computationally time-consuming and needs more data to produce accurate results. 

* <b> Time to setup: </b> Setting up a random forest takes only a short amount of time, but some hyperparameters must be tuned, including the number of trees, the number of characteristics to be taken into account at each split, and the minimum number of samples needed to split a leaf node.

* <b> Time to produce results: </b> Random forests are computationally demanding and take a long time to train, especially when dealing with huge datasets. But once the model is trained, making predictions happens rather quickly. 

* <b> Output: </b> The Random Forests' results are a probability of customer churn. Additionally, it is an effective ensemble method that can capture the nonlinear relationship between the independent and dependent variables, which can raise prediction accuracy.

* <b> Strengths: </b> It is simple to comprehend and implement, has straightforward results to interpret, and can handle both linear and non-linear correlations between variables.

* <b> Weaknesses: </b> Assumes linearity between the independent variables and the log odds of the dependent variable, may not perform well on highly non-linear data.

* <b> Data types (input & output): </b> Requires input data that can be categorical or numerical, and the result is either a class label or a number value for regression.

It's crucial to remember that while Random Forests is a powerful technique, it requires more data and computational resources than Logistic Regression and is more difficult to set up. Before making a decision, it's crucial to assess the model's performance on a holdout set or via cross-validation.

</font> </p>

<h5> <b> 3. Gradient Boosting for Customer Churn Prediction </b> </h5>

<p> <font size='3'>

Another ensemble technique, gradient boosting, mixes different decision trees to boost the prediction accuracy. Making accurate predictions about which customers are most likely to churn would be the aim of employing this technique, which aims to find patterns in customer data.

By calculating a weighted average of all the ensemble's trees' predictions, the final conclusion can be drawn. Various predictive tasks, including predicting customer churn, have proved to benefit greatly from gradient boosting.

Below, said model has been evaluated in terms of data availability, time to setup, time to provide results, output, strengths and weaknesses and data types of the inputs and outputs of the model.

* <b> Data availability: </b> Gradient boosting can be identified as a technique that could handle both large and small scale datasets. However, it is necessary to point that it requires large amounts of computational power and requires more data to achieve good results compared to logistic regression.

* <b> Time to set up: </b> Gradient boosting can be considered time consuming to set up, as it requires several hyperparameter tunings such as the number of trees, depth of the trees and the learning rate.

* <b> Time to produce results: </b> Gradient boosting can be intensely  computational and require a recognisable time to train, especially when dealing with large datasets. However, it becomes much faster to make predictions once the model is trained and validated.

* <b> Output: </b> The output of the said technique is a probability or the likelihood of a certain customer churning. It is also a powerful ensemble method that could detect non-linear relationship between the independent and dependent variables which improves the accuracy of the predictions made by the model.

* <b> Strengths: </b> Possesses the ability to manage high-dimensional data, handle missing values, and manage both categorical and numerical data. 

* <b> Weaknesses: </b> Having too many trees can lead to overfitting, it can be expensive to compute, and it might not be able to capture intricate relationships between variables.

* <b> Data types (input & output): </b> Also requires input data that can be categorical or numerical, and the result is either a class label or a number value for regression.

Gradient boosting can be monitored to avoid overfitting by early stopping and shrinkage. Gradient Boosting is a strong technique, but it is more difficult to set up and requires more data and processing capacity than Logistic Regression, which is crucial to keep in mind. A holdout set or cross-validation should be used to assess the model's performance before making a final choice.


</font> </p>

<p> <font size='3'> All three of these methods can generally be used with similar sorts of input data, however the expected results can differ depending on the problem or the scenario selected. Random forests and gradient boosting are used for both binary and multi-class classification as well as regression, whereas logistic regression is mostly utilized for binary classification. Therefore, the selected technique to implement is the <b> Logistic Regression </b> technique. </font> </p>
