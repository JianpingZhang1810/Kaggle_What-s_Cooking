# Kaggle_What's_Cooking
My final project of EECS349
  
### Introduction of dataset

In this project I use kaggle What's cooking dataset, containing more than 3000 cooking receipts of a specific cuisine and ingredients, to predict cuisine of a given ingredients recipe. relative link https://www.kaggle.com/c/whats-cooking
Data has the following form
 
 {
 "id": 24717,
 "cuisine": "indian",
 "ingredients": [
     "tumeric",
     "vegetable stock",
     "tomatoes",
     "garam masala",
     "naan",
     "red lentils",
     "red chili peppers",
     "onions",
     "spinach",
     "sweet potatoes"
 ]
 },
 
 The result is evaluated on the categorization accuracy (the percent of dishes that you correctly classify), which has the following form.
 
 id,cuisine
35203,italian
17600,italian
35200,italian
17602,italian

### Methods
1 Using Bag of Word model represents all indredients and sparse vector represents a repipe. Then I use random forest and logistic regression to see the basic performance as the baseline.
