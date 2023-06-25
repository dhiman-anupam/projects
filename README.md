

**1. Analyzing 1000 Data Science Books on Amazon**

To explore a little bit about what kind of data science books are available out there, i found a data set on kaggle that contained data on nearly 1000 data science books on Amazon, including the ratings, the price, the number of pages and other characteristics.

In this project i will be doing two levels of analysis-what i would call basic and intermediate.

On level 1, i will do some simple exploratory data analysis to answer questions like do more expensive books have better reviews? Is it always true that longer books are more expensive? What are the best python related books and what are the best machine learning books based on review stars?

Moving on to level 2, i start getting a bit more fancy. i want to find out what are the main types or main categories of data science books out there based on the book titles. I will be using k-means for clustering the book titles and in order to do that for text data, i use an NLP technique called TFIDF or term frequency inverse document frequency to convert the text into numeric features.



**2.WATER QUALITY PREDICTION**

Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.

**THE GOAL OF THIS PROJECT IS TO FIND THE QUALITY OF WATER USING VARIOUS MACHINE LEARNING ALGORITHMS AND TO FIND OUT WHICH ONE IS THE BEST MODEL AMONG ALL OF THEM**

WHAT I HAD DONE

•	Discussed some major columns on which quality depends.
•	Handling outliers of diagnosis columns. As, it is very important because at last we're predicting quality.
•	Then I used different classification models present in sklearn to train the model.
•	Use Correlation coefficients to measure how strong a relationship is between two variables.

MODELS USED

•	Logistic Regression
•	Support Vector Machine (SVM)
•	Decission Tree
•	K Nearest Neighbour
•	Naive Bayes
•	Random Classifier

LIBRARIES NEEDED

•	numpy
•	pandas
•	seaborn
•	matplotlib
•	scikit-learn

CONCLUSION 

By using Logistic Regression I got
Accuracy of training data: 59.68819599109132
Accuracy of testing data: 59.93975903614458
By using Support Vector Machine (SVM) I got
Accuracy of training data: 59.68819599109132
Accuracy of testing data: 60.09036144578314
   
By using Decision Tree I got
Accuracy of training data: 100.0
Accuracy of testing data: 99.54819277108435
   
By using K Nearest Neighbour I got
 Accuracy of training data: 70.97253155159613
Accuracy of testing data: 57.07831325301205  
By using Naive Bayes I got
Accuracy of training data: 62.28656273199703
Accuracy of testing data: 62.34939759036144
   
By using Random Classifier I got
Accuracy of training data: 100.0
Accuracy of testing data: 83.58433734939759
