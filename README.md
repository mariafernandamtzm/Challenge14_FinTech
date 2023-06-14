# Challenge14_FinTech

This repository offers code and guidelines for analyzing a trading algorithm's performance using machine learning methods. The sections of the evaluation procedure are as follows:

## Technologies and Languages Used
* Python
* Jupyter Notebook
* Pandas
* scikit-learn (SKLearn)
* Matplotlib

## Steps to Follow
1. Establish a Baseline Performance
Run the provided starter code to establish a baseline performance for the trading algorithm.
Import the OHLCV dataset into a Pandas DataFrame.
Generate trading signals using short- and long-window SMA values.
Split the data into training and testing datasets.
Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data.
Review the classification report associated with the SVC model predictions.
Create a predictions DataFrame that contains columns for "Predicted" values, "Actual Returns", and "Strategy Returns".
Create a cumulative return plot that shows the actual returns vs. the strategy returns and save it as a PNG image.

2. Tune the Baseline Trading Algorithm
Tune the training algorithm by adjusting the size of the training dataset.
Tune the trading algorithm by adjusting the SMA input features.
Choose the set of parameters that best improved the trading algorithm returns.
Save a PNG image of the cumulative product of the actual returns vs. the strategy returns.

3. Evaluate a New Machine Learning Classifier
Import a new classifier, such as AdaBoost, DecisionTreeClassifier, or LogisticRegression.
Fit another model with the new classifier using the original training data as the baseline model.
Backtest the new model to evaluate its performance.

4. Create an Evaluation Report
Add a summary evaluation report at the end of the README.md file.
Express your final conclusions and analysis.
Support your findings by using the PNG images that you created.


# Conclusion
In conclusion, this study offers a framework for assessing a trading algorithm's performance using machine learning methods. It enables comparisons and improvements in trading outcomes by setting a baseline performance, fine-tuning the algorithm, and testing various classifiers. The evaluation report summarizes the results and offers information on the trading algorithm's efficacy when used with various settings and classifiers.
