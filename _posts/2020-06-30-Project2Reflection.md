---
layout: post
title: Reflection on Project 2
---

My experience in Project 2 is of more fun than struggle! Now I have a better understanding of connecting RStudtio to Github, Creating Github Page, and also keeping version control along the way! Here are some reflection points:  
1) **Automatic RMarkdown**: When I first heard about it in the lecture, it was so vague to me. I knew it for the existence, but had no idea how to really apply it. With this project, I re-listened the lecture, and figured out my way! It's very helpful, in my perspective, when we have large amount of reports to generate. It made the whole R markdown file as a "giant function", and input with different paramemter values to get versatile result.  
2) **Ensemble vs Regression Model**: I used Bagged Tree as Ensemble model, and Logistic Regression with stepwise selection for Regression Model. The Regression model looks less likely to be overfitting (based on training data), while the Bagged Tree is normally very overfitting. The miss-classfication rate of Bagged tree model can be as low as 1% on training data, while same metric is 35% ish on Logistic Regresssion Model.  
3) **Efficient Computation**: The process of knitting is long as I use *CARET* package to find the best combination of predictors. I am wondering if I can use parallel computing or som e other ways to make the compuation more efficient.

