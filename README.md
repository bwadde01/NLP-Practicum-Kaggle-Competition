# NLP-Practicum-Kaggle-Competition
I placed 1st in a Kaggle competition as the capstone for an NLP Practicum and have posted my notebook here. 
The competition was to predict the sentiment of IMBD movie reviews based on the text content of the review;
evaluation was based on F1 score, training data included 40,000 reviews.
For more information, you can find the competition here: https://www.kaggle.com/c/us-nlp-practicum-2020-a

I initially tried to get to a baseline performance using a Naive Bayes classifier after pre-processing the data
(cleaning for punctuation, special characters, html tags, etc.; lemmatizing with part of speech tagging for 
words that share meanings based on roots; removing stopwords) and achieved ~89% F1-score after hyperparameter 
optimization. I also tried a few other models (random forests, svc, etc. which had similar or inferior performance).

To improve the performance, I turned to deep learning approached with the ANN. After determining a fitting 
architecture, I achieved my best performing model yet with an F1-score of ~91.2%. 

After this, I experimented with other methods to improve accuracy, namely data augmentation and ensembling. 
With these methods, I was able to improve performance to 92.266% and win the competition. Check out the 
notebook!
