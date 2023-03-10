# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3
# Regression and classification with housing data

## Business Case

You work for a real estate company interested in using data science to determine the best properties to buy and re-sell. Specifically, your company would like to identify the characteristics of residential houses that estimate the sale price and the cost-effectiveness of doing renovations.

There are three components to the project:

1. Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. 
3. Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).

This project uses the [Ames housing data recently made available on kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

---

## Directions

Though the housing data for this project is very rich, it is not trivial to clean and prepare for modeling. Good EDA, cleaning, and feature engineering will be critical to the success of your models. Always remember to think critically about the data before modeling. The computer can't be the researcher for you!

The first two parts of the project are regression problems. There are potentially hundreds of features and plenty of multicollinearity, so regularization is definitely recommended.

The third section of the project is more challenging and involves dealing with significant class imbalance. This is a common and tricky problem in real-world classification tasks. We leave it up to you to decide how you want to tackle this problem and devise a solution, and highly recommend doing your own research into the topic.

We will be looking for the following things:

- Detailed EDA with justification for the steps. Visualize your data with pandas, matplotlib, or other plotting libraries. Explain the variables you choose for your models.
- Detail your choice of regression and classification models for the task. Include Markdown explaining your justification, results, and interpretation of your models. Make sure your code is clean and clear.
- Remember to frame your results according to your goals outlined in the project prompts.

---

## Requirements

- Materials must be in a clearly commented Jupyter notebook
- You should demonstrate the ability to:

1. Analyze a complex dataset & explicitly state your assumptions.
2. Clean, impute, and explore the dataset.
3. Justify your modeling choices and feature engineering.
4. Plot, visualize, and interpret your data logically.
5. Clearly outline your modeling strategy in response to the questions
6. Explain your results to a technical audience.

---

## Project Feedback + Evaluation

For all projects, students will be evaluated on a simple 3 point scale (0, 1, or 2). Instructors will use this rubric when scoring student performance on each of the core project **requirements:**

Score | Expectations
----- | ------------
**0** | _Incomplete_
**1** | _Does not meet expectations_
**2** | _Meets expectations, good job!_
