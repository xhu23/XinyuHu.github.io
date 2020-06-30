---
layout: post
title: Reflection on Project 2
---
**Link to Project2 HomePage**: [https://xhu23.github.io/Project2/](https://xhu23.github.io/Project2/)  

My experience in Project 2 is of more fun than struggle! Now I have a better understanding of connecting RStudtio to Github, Creating Github Page, and also keeping version control along the way! Here are some reflection points:  
1) **Automatic RMarkdown**: When I first heard about it in the lecture, it was so vague to me. I knew it for the existence, but had no idea how to really apply it. With this project, I re-listened the lecture, and figured out my way! It's very helpful, in my perspective, when we have large amount of reports to generate. It made the whole R markdown file as a "giant function", and input with different paramemter values to get versatile result.  
2) **Ensemble vs Regression Model**: I used Bagged Tree as Ensemble model, and Logistic Regression with stepwise selection for Regression Model. The Regression model looks less likely to be overfitting (based on training data), while the Bagged Tree is normally very overfitting. The miss-classfication rate of Bagged tree model can be as low as 1% on training data, while same metric is 35% ish on Logistic Regresssion Model.  
3) **Efficient Computation**: The process of knitting is long as I use *CARET* package to find the best combination of predictors. I am wondering if I can use parallel computing or som e other ways to make the compuation more efficient.  

*what would you do differently?*  
I think I am good with the time I started with this project. The thing I would do differently is thinking about the "versatility" of the RMarkDown file in the very begining. Starting with Monday day is easier to put hands on. But without bearing the idea of conversion, I spent quite some time on convert it to a general weekday report.  

*what was the most difficult part for you?*  
Well, I think the most difficult part was the automatic md file creation! I wasn't so sure about the process, and sepnt lots of time figuring out step by step. And also in that process, I messed up with the Github versiion control. So I have delete the whole repository to start over. But it's a great learning though!  

*what are your big take-aways from this project?*  
Starting early woulf always be helpful! I started early this time, and felt confident about the time along the way. Also, practice is more important than I imagine. The automatic rmarkdown process is learnt in lecture, but really understood by practice.  

Thanks for providing such good learning experience!

