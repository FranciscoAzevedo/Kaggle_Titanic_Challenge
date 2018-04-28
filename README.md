# Kaggle_Titanic_Challenge
Code for the Kaggle_Titanic_Challenge using scikit-learn and pandas. Ran with jupyter notebook

Kaggle is an online competitions host for data science and machine learning. One of its introdutory challenges is the Titanic one in whihc you need to predict if a given person has died or lived based on a few inputs (name, title, ticket fare, age, passenger class etc.). 

I entered this competition with the objective to learn to apply machine learning models to data science in real cases because I've already studied the theory behind most concepts (decision trees, NN, SVM, Random Forests, Bagging etc.)

# Frameworks and tools

I used jupyter notebooks to run the code online and vizualize it. I used scikit-learn to apply the models, pandas to handle the data and Matplotlib/Seaborn for vizualization (but Im still quite ignorant about these vizualization tools...).

This was my first time using pandas and also the vizualization tools. I think for wrangling data pandas is probably the go to for its simplicity and power. I think theres probably better vizualization tools out there like plotly.

# Method applied

1 - See the data: Open, check some features and their distributions, see if there are NaN's

2 - Fill the data: Choose a method (mean, median, or other) to fill the NaN's or discard those features

3 - Feature Engeneering: Extract, create and convert features to have all of them in numeric form

4 - Apply the models: Pick the models you know and just give'em data

5 - Evaluate and Improve: Test the models and use cross-validation to tune the hypeparameters of the best models

6 - Rant:   I dont like most ensemble ideas like boosting,bagging or *sigh* stacking. To me its just a quick way to up 
            your algorithms performance as if it was a black box model to sell to a company. There's some empirical background
            for those methods (decrease model variance in bagging and bias in boosting) but it still feels cheap.

7 - Be dirty, Stack those models: Disregard any moral or academic values and just apply gradboost and (hard) stack your top5 models

# What I've learned

I lied a bit in this read.me, I've already done some kaggling with a friend of mine but he did most of the work. During that
time I realized that the most important skills to retrieve from these kind of  competitions is not the raw frameworks/tools knowledge or the fame of being the top 10% overfit winner but rather to be able to understand how to study and process data aswell as to learn to debug and evaluate your model. I feel that I've learned quite a bit of that during this competition and hope to apply it further in the future challenges.
