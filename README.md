# RStudio
Projects completed in RStudio

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [HomeworkR](#HomeworkR)
- [MachineLearningProjects](#machinelearningprojects)
- [Contributors](#contributors)
- [License](#license)
- [Contact](#contact)

## Introduction

Welcome to the **RStudio Repository**! This repository contains a collection of assignments and projects from the Data 101 course, focusing on fundamental principles of data analysis and statistical computing using R. Each assignment is meticulously designed to help you grasp essential concepts such as data manipulation, visualization, statistical modeling, and more.

Whether you are a beginner looking to strengthen your understanding of R or an experienced data scientist revisiting the basics, this repository will be a valuable resource. Let's dive into the fascinating world of data science with R through a structured and comprehensive set of assignments.

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [R](https://www.r-project.org/) (Version 4.0 or higher).
- You have installed [RStudio](https://www.rstudio.com/) (recommended for an integrated development environment).
- You have access to a terminal or command line interface.

### Step-by-Step Installation

1. **Clone the Repository**

    First, you need to clone the repository to your local machine. Open your terminal and run the following command:
    ```bash
    git clone https://github.com/yourusername/yourproject.git
    ```

2. **Open RStudio**

    Open RStudio and load the project by selecting the `.Rproj` file within the project directory.

3. **Install Required Packages**

    Ensure you have the required packages installed. You can use the following command to install all the necessary packages:
    ```r
    install.packages("package")
    ```
    
## HomeworkR

The `HomeworkR` folder contains several R scripts designed to perform various statistical analyses using a range of libraries and packages. These scripts illustrate fundamental and advanced statistical methods, making use of widely-used R libraries such as `EnvStats` and `faraway`.

### Libraries and Packages
The `R` scripts in this folder leverage powerful libraries and packages to execute statistical tests and create visualizations. Some of the key libraries include:
- **EnvStats:** This library provides functions for environmental statistics, including estimation, hypothesis testing, and graphical procedures.
- **faraway:** This package contains datasets and functions for the book "Linear Models with R" by Julian Faraway, and it is useful for regression analysis and model diagnostics.

### Statistical Analysis
The scripts in `HomeworkR` cover a wide range of statistical techniques, including:

- **Chi-Square Tests (chisq tests):** Used for testing the independence of two categorical variables. The chi-square test determines if there is a significant association between the variables.
- **Single/Two-Sample Permutation Tests:** These non-parametric tests are used to compare groups when the assumptions of traditional parametric tests (like t-tests) are not met. Permutation tests rely on the rearrangement of data to assess the significance of observed differences.
- **Random Uniform Distribution (runif):** This function generates random numbers from a uniform distribution, which is useful for simulating data or random sampling.
- **Quantile-Quantile Plots (qqplots):** QQ plots are graphical tools used to assess if a dataset follows a specified distribution, such as normality. They compare the quantiles of the data to the quantiles of a theoretical distribution.
- **Proportion Tests (prop.test):** This function tests the null hypothesis that the proportions in several groups are the same, or that they equal specified values.
- **Confidence Intervals (conf.int):** Confidence intervals provide a range of values that likely contain the population parameter. They offer a measure of uncertainty around the estimate.

## MachineLearningProjects 
The `MachineLearningProjects` directory encompasses several projects that utilize a similar approach to develop RPart trees for predicting various outcomes. Below is a detailed description and analysis of Project 3. 
- **Project 1: Predicting Earnings** This project focuses on predicting individuals' earnings using RPart trees. The objective is to explore the effectiveness of recursive partitioning in forecasting financial outcomes based on various predictors.
- **Project 2: Predicting Price of Clothes** The second project aims to predict the price of clothing items. By experimenting with RPart trees, the project evaluates the model's accuracy and ability to capture the relationship between different attributes of clothing and their corresponding prices.
- **Project 3: Predicting Loan Approval** The third project is dedicated to predicting whether a customer should receive a financial loan (1 for yes, 0 for no). This project serves as a more comprehensive analysis,

### Dataset Composition

**Variables Considered:** The dataset includes key variables like credit score, mortgage, and income, which are crucial indicators of an individual's financial health and liability status. Additional variables such as family size, education, age, and experience provide a more comprehensive profile of the customers, but may not be as useful for helping predict whether they should get a financial loan.

**Entries:** The dataset comprises 5000 entries, with 70% (3500 entries) designated for training the model and 30% (1500 entries) reserved for testing its accuracy.

### Prediction Model

**Initial Model:** The initial prediction model used basic variables (credit score, mortgage, and income) to predict loan approval, resulting in a mean squared error (MSE) of 0.09. This indicates that, on average, the predictions deviated from the actual values by 0.09.

**Refined Model:** The refined prediction model incorporated additional variables—credit score, family size, income, education, age, and experience—to enhance its accuracy. This comprehensive approach reduced the MSE to 0.01237153, demonstrating a significant improvement in predictive accuracy.

### Methodology

**Data Splitting:** The dataset was divided into training and testing sets in a 70:30 ratio. The training set, consisting of 3500 entries, was used to develop the prediction model. The testing set, with 1500 entries, was employed to evaluate the model's performance and generalizability.

### Conclusion

The substantial reduction in MSE from 0.09 to 0.01237153 highlights the effectiveness of incorporating a broader range of variables in the prediction model. This approach provides a more accurate and reliable tool for predicting loan approval, ultimately benefiting both the financial institution and its customers.

### Model Evaluation and Comparison

Implementing a decision tree model using the `rpart` (recursive partitioning) package achieved an impressive accuracy of approximately 98.4%. In contrast, the Naive Bayes model attained an accuracy of around 81.68%. 

**Performance Analysis**

**Decision Tree Model:**
- **Accuracy:** The decision tree model, constructed with `rpart`, demonstrated a high accuracy of 98.4%. This model's complexity allows it to capture intricate relationships and dependencies within the data, contributing to its superior performance.
- **Complexity:** Decision trees are inherently capable of handling complex data structures and interactions between variables. This complexity enables the model to provide more accurate predictions by considering the combined effects of multiple features.
- **Dependence:** Unlike simpler models, the decision tree does not assume independence among features. It can effectively account for the dependencies and interactions between variables, making it a more robust and reliable predictor.

**Naive Bayes Model:**
- **Accuracy:** The Naive Bayes model, while relatively simpler, achieved an accuracy of 81.68%. Although this is a decent level of accuracy, it falls short when compared to the decision tree model.
- **Simplicity:** The Naive Bayes classifier operates under the assumption that all features are independent. This assumption can limit the model's performance, especially in real-world datasets where features often exhibit dependencies.
- **Independence Assumption:** The independence assumption of Naive Bayes can significantly affect its accuracy. By ignoring the interdependencies between features, the model may miss important interactions and relationships, leading to less precise predictions.

**Conclusion:**

When comparing the accuracy of the two models, it is evident that the decision tree model significantly outperformed the Naive Bayes model. The decision tree's ability to handle complex interactions and dependencies within the data contributes to its higher accuracy. In contrast, the Naive Bayes model's assumption of feature independence can limit its predictive power.

The decision tree's enhanced performance underscores the importance of considering feature dependencies and interactions in predictive modeling. By capturing these intricate relationships, the decision tree provides a more accurate and reliable tool for making predictions.



## Contributors
Rutgers Computer Science Department
https://www.kaggle.com/datasets

## License
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

## Contact
vishalsaran2021@gmail.com
