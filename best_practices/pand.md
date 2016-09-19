# Introduction
This document serves as the handbook for forum mentors for the Predictive Analytics for Business Nanodegree (PAND) program. We want to set common guidelines and expectations for all mentors to ensure:

1. Clear communication guidelines between mentors, students, and Udacity
2. Consistent and high quality instructions
3. Mentors have all the resources they need to teach our students

# Proper Mindset and Tone
Teaching students Predictive Analytics in the field of Business requires a blended teaching framework between teaching precision data analysis and subjectiveness of business. 

Therefore when you teach students, always think about the situation and context they are working in these projects. The data will not be perfect and will often never be enough and what matters more to business leaders is that the business analyst provide a clear direction to help guide business leaders to make their business decisions. Therefore, it’s less important to be 100% precise with the numbers and more important to look at a situation and make a recommendation of what decision businesses should make.

The tone you should have when you interact with students is of a friendly guide suggesting and guiding students to think deeper about their assumptions, ultimately helping them make the decisions they need about their analysis. As guides, we cannot tell the student to do anything and we shouldn’t. We can always share our experiences, offer suggestions, challenge their assumptions, and lead students down a path where they can answer their own questions - we simply point them in the right direction.
# Important Context
If you’re coming from a data science or machine learning background, please be mindful that the curriculum is not as rigorous compared to the Data Analyst or Machine Learning Nanodegree programs!

As you guide students, be very careful introducing topics that students will not be familiar with. Furthermore, do not expect students to be able to code or derive insights from any resources that are math heavy. This Nanodegree program is designed for business professionals who do not have a background in coding and do not have a recent background in mathematics or statistics. Therefore the curriculum is designed around giving students the intuitive sense of what predictive models do without focusing on math heavy topics, granular assumptions related to predictive models, and programming.

Your challenge is to distill down the mathematical concepts into an intuitive sense for these students.

Therefore we encourage you to skim the course content in this Nanodegree here to understand how we’re using Alteryx to teach these predictive models. This will also help give you the key points in the courses to reference to when you’re instructing students. [Alteryx](https://www.alteryx.com) is an analytical software that puts an easy graphical user interface on top of R’s predictive libraries.

[Problem Solving with Advanced Analytics](https://classroom.udacity.com/courses/ud976)
[Creating an Analytical Dataset](https://classroom.udacity.com/courses/ud977)
[Visualization with Tableau](https://classroom.udacity.com/courses/ud1006)
[Classification Models](https://classroom.udacity.com/courses/ud978)
[A/B Testing](https://classroom.udacity.com/courses/ud979)
[Time-Series Analysis](https://classroom.udacity.com/courses/ud980)
[Segmenting and Clustering](https://classroom.udacity.com/courses/ud981)

Here is a list of concepts that students will learn throughout the Nanodegree program. If you do not see a concept listed down here such as (residuals, homoscedasticity, log-transforms, ordinary least squares, etc.), refrain from using these concepts as a requirement for them to understand and pass the project. 

Note: We assume students will be familiar with basic inferential and descriptive statistics.

* Quartiles and Box-Whisker plots
* Normal distribution
* Linear regression
* Multi-variable linear regression with categorical variables
* Linear relationship assumption between target variable and predictor variable (feature)
* Outlier analysis using the Interquartile Range method
* Imputation using mean and linear regression
* Multicollinearity and Pearson Product-Moment correlation
* Logistic Regression
* Decision Trees
* Random Forests
* Boosted Trees
* Accuracy with confusion matrices and precision bias
* ROC Curve and Area Under Curve
* Gain and Lift charts
* False positives and True positive charts
* A/B testing: randomized-design and matched-pairs
* Control variables for A/B testing
* Calculate incremental lift for A/B testing
* T-tests
* Time-series forecasting using ETS and ARIMA models
* Moving-average
* Auto-correlation
* Differencing
* Stationarity
* K-means clustering and segmentation
* Hierarchical clustering


You are welcome to mention additional concepts and link students to additional resources to improve their analysis, but make sure to explain it in an intuitive manner and refrain from using math heavy terms. Please be sure to link to resources that are not too math heavy.

If you have questions on whether your comments are too advanced for the students, please share your typed up comments in the Mentor Slack channel here: #pa-for-business for everyone to look over your response.

# Forum Training

This section is contains example posts for the most common questions you will face while helping students.

As part of your training, please go through each of these sample posts and write a response to the student. Type up your answers and send them to bizanalyst-projects@udacity.com and our service staff will look over your answers and provide you feedback.

**Notes:**

You are not required to know how to troubleshoot technical questions relating to the Alteryx and Tableau software. If you do not know the answer, feel free to point the student to the appropriate technical support channels that Alteryx and Tableau has:

Alteryx: http://www.alteryx.com/support

Tableau: https://www.tableau.com/support/request

If you’re not familiar with the Alteryx software, we encourage you to first get familiar with this software and take the first two courses:

[Problem Solving with Advanced Analytics](https://classroom.udacity.com/courses/ud976)
[Creating an Analytical Dataset](https://classroom.udacity.com/courses/ud977)

The software is free to download and use for 14-days.

##Post #1

I can’t seem to get the right answer to the Linear Regression quiz. Can anyone help me?

##Post #2

Help! I get this error message when trying to run this visualization tool I found. Please help!

![](http://i.imgur.com/zedZphO.png)

##Post #3

I’m having trouble with understanding the math behind ln(p/(1-p)) = b0 + b1x1 + b2x2 for a logistic linear regression. I have used Alteryx to create the model but am not sure how to translate the coefficients into the right places in this equation.

So my intercept is 200.76. I know this equals b0.

I have three categorical options to use for the x2 number. I know the two remaining numbers are my other constants, they are 48.81, -24.22, and 0

What I don't know is how to determine what x should be that goes with which coefficients.

Here is the print out of the model in Alteryx:

- Intercept -> 200.76
- Default_Loan -> 94
- LoanType_Lease -> -24.22
- LoanType_Finance -> 48.81

If the problem does not indicate it obviously does that mean I don't have what I need to complete the equation?

##Post #4

How does the Alteryx report calculate the accuracies from this confusion matrix for Yes and for No? Doesn’t accuracy relate to how many Yes’s you can predict over the total number of data points you have?

**Alterx reports:**

Predicted_Yes accuracy: 92%
Predicted_No accuracy: 93%

But I’m calculating Predict_Yes accuracy to be: 284/515 = 55%

|  | Actual_Yes | Actual_No |
| -- | -- | -- |
| Predicted_Yes | 284 | 25 |
| Predicted_No | 14 | 192 |


# Post #5

I’m having trouble figuring out outliers for Project 2. The project says that I need to remove only one outlier out of 11 rows, but I don’t know where to begin on how to choose which outlier. 

I’ve calculated 4 outliers but have no clue which outlier should I remove because they all skew differently in different data fields. Where do I begin?

I’m thinking of Cheyenne, but I heard from other students that Cheyenne should not be removed. Why is that?

City
Sales
Population
HH_Income
Density
Gillette
Skew High






Cheyenne
Skew High
Skew High
Skew High
Skew High
Rock Springs




Skew High


Eagle Lake






Skew High

Post #6

I’m having trouble removing the first quotation mark in my data such as:

“Name_Goes_Here’

What’s the formula to do exactly this?