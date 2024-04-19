# NTU-SC1015-Steam-Data-Insights-
![STEAM Stock Image](images/steam_stock_photo.jpg)

## Contributors
- Soh Zi Xiang - Review Sentimental Analysis, LDA, Random Forest Classifier
- Teng Zi En - Steam Games Data Analysis, Visualization of the Relationship between Numeric/Categorical Columns with number of Positive & Negative Reviews
- Tan Kia Chun - Developed the Positive Negative Review Prediction model using decision tree classifiers, and managed data preprocessing and feature selection.

## Problem Definition
As avid gamers, we sometimes wonder why is certain games so popular, and to answer that question, we tend to look at the reviews to find out what sets games apart from the rest. But what exactly affects reviews? This leads out to our problem statement, we want to find out how does different features such as Publishers, Categories, DLC count, User score etc. affects review sentiment. But why reviews? 

Both positive and negative reviews are able to contribute to different outcomes for different stakeholders. Positive reviews contribute to higher sales and user engagement, while negative reviews can indicate areas for improvement and potential revenue loss. By predicting sentiment, stakeholders can make informed decisions regarding game development, marketing strategies, and platform enhancements. Therefore, our project aims to analyze sentiments in user-generated Steam reviews, seeking to offer valuable insights for gamers and developers alike.

## Conclusion
In the end, focusing on what players really care about—like making controls easier, improving graphics, and creating fun gameplay—can lead to better reviews for developers. By making games more accessible, listening to players, testing games well, and building strong communities, developers can make sure players love their games and give them great reviews

The pivotal role that nuanced features like 'Game Age' and 'Achievements' play in predicting game reviews, with the models achieving up to 76% accuracy. The insights gained underscore the potential of machine learning to guide game development and marketing strategies. 

Publishers have the greatest influence on review count as people will tend to play games published by popular publishers. This is due to their reputation and their successive track records in publishing games that are successful in the gaming market.

## What did we learn from this project?
- Handling imbalanced datasets using resampling methods using SMOTE, RandomUnderSampler & Pipeline
- Word Cloud visualization
- Latent Dirichlet Allocation (LDA) using Gensim
- Concept of F1 Score 
- Integration using github
- Feature Importance Understanding
- Data Preprocessing
- How to collect, analyse and clean a huge dataset to suit our needs and answer our problem
- Formulating out different ways to solve the same problem, to find out the best relation between 2 variables 

## References
- [Topic Modeling and Latent Dirichlet Allocation (LDA) using Gensim and Sklearn](https://www.analyticsvidhya.com/blog/2021/06/part-2-topic-modeling-and-latent-dirichlet-allocation-lda-using-gensim-and-sklearn/)
- [Topic Modeling with Gensim in Python](https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/#15visualizethetopicskeywords)
- [Unsupervised NLP: Topic Models as a Supervised Learning Input](https://towardsdatascience.com/unsupervised-nlp-topic-models-as-a-supervised-learning-input-cf8ee9e5cf28)
- [Steam Reviews Dataset](https://www.kaggle.com/datasets/andrewmvd/steam-reviews)
- [Steam Games Reviews Analysis - Sentiment Analysis](https://www.kaggle.com/code/danielbeltsazar/steam-games-reviews-analysis-sentiment-analysis)
- [README Image](https://unsplash.com/photos/a-computer-mouse-on-a-white-surface-ODDeVEZGEfs)
- ["5 Most Useful Techniques to Handle Imbalanced Datasets"](https://www.kdnuggets.com/2020/01/5-most-useful-techniques-handle-imbalanced-datasets.html)
