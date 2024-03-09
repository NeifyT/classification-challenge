# Email Classification—spam or not spam?

   ### CONTENTS
**[The Challenge](#the-challenge)**<br>
**[Personal Interest](#personal-interest)**<br>
**[Starter Code](#starter-code)**<br>
**[Challenge Checklist](#challenge-checklist)**<br>
**[Running the Program](#running-the-program)**<br>
**[Data Analysis Answers](#data-analysis-answers)**<br>

## The Challenge

Create two supervised machine learning models that will classify whether an email is spam or not. Determine then, which model works best. The two models that are to be used are a logistic regression model and a random forest model.

## Personal Interest

This challenge interests me personally beyond the machine learning exercise. The two things of our digital age I detest the most are spam filters followed by spam itself. It has been my personal experience that spam filters never really work. At best they may cut out 50% of spam while blocking important legitimate email 1% to 2% of the time. If one increases the filter strength even more legitimate email gets blocked. The only way to ensure legitimate and often extremely important email does not get blocked is to eliminate all spam filters completely. The way I have avoided the spam/spam-blocker dilemma is to institute a policy of disposable single-use email addresses. I give out a single-use email address to any business I need to work with, if they send unwanted spam and/or leak/sell my address to a spammer I delete the email address and not lose contact with anyone else.

Perhaps I will find machine learning has come far enough to finally solve the spam dilemma. Or, perhaps this exercise will only strengthen my bias against spam filters. I note two main problems. First, that the test data stems from 1999 and email spam has evolved tremendously in the last 25 years, making this data not valid.  Second, I note that the data has been encoded into a proprietary format which appears only to word count an extremely few common words found in email back in the 90s. In order for a machine learning model to really be successful with today's spam it would have to not rely on word counts at all, and would need to utilize some form of a large language model.

Yet, despite the irrelevancy of the data, the challenge is something I am passionate about and may play around with real world current data using my own encoding method, separately or attached to this challenge.

## Starter Code

The starter code for this challenge consists of a notebook file (.ipynb) which will run in Jupyter, Jupyter Lab, or VS Code with Jupyter extensions. The notebook contains code commenting and markdown to match the workflow of the challenge, questions for answering, initial code to import packages, read and display the initial data set, and expected cell outputs.

## Challenge Checklist

This challenge seems simple compared to the last.

### Step 1: Split the Data (Training/Testing)

- [x] Read in static data
- [x] Make initial prediction which of the two models will be better
- [x] Separate data into features (X) and target (y) values
- [x] Check the balance of y values
- [x] Split the data into training and testing sets

### Step 2: Scale the Features

- [x] Instantiate StandardScaler
- [x] Fit the training data
- [x] Scale training and testing data

### Step 4: Create a Logistic Regression Model

- [x] Fit training data to model with random state 1
- [x] Save predictions of testing data
- [x] Evaluate performance

### Step 5: Create a Random Forest Model

- [x] Fit training data to model with random state 1
- [x] Save predictions of testing data
- [x] Evaluate performance

### Step 6: Evaluate Models

- [x] Answer: Which model performed better?
- [x] Answer: How does that compare to your prediction?


## Running the Program

The program folder contains the completed notebook which can be run cell by cell from and results displayed in Jupyter, Jupyter Lab, or VS Code with Jupyter extensions.

```
spam_detector.ipynb
```

The outputs for all cells in the notebook have been saved to retain any possible anomalies between different package versions. Specifically, I note a slight difference in accuracy scores between Scikit-Learn versions 1.3 and 1.4 (with 1.3 being slightly better). The notebook cells could be run from top to bottom. Outputs will closely resemble those displayed in the original starter code file, but may vary.

## Data Analysis Answers

Answers to the questions will be saved within the notebook in their associated markdown cells.