# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Bedrooms
2. Bathrooms
3. Age
4. Least Important: SquareFeet

**Explanation:**

I determined this ranking by the coefficients, because the higher the coefficient the more important it is except in the case of age vs squarefeet because the age of the house decreases the value. I then had to determine which one was most important by using the absolute value.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional bathroom increases the price by $3858.90

**Feature 2:**
Each additional year for the age of the house decreases the value by $950.35

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**

My models R^2 score was .9936 which rounds to 1. This means that my model is nearly perfect at predicting the house prices. There is room for improvement though because my Root Mean Squared Error is $4477.89.


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
County/ Its crime rate

**Why it would help:**
The higher the crime rate the less valuable it is so I would use a coefficient similar to the age one. 

**Feature 2:**
How many floors

**Why it would help:**
Floors would include attics and basements which would then add more value to the house.

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would trust this model to predict this situation but I would have a few doubts since my training doesnt cover something on this large of a scale. I believe the error percentage would raise a bit higher but that's fine. 

