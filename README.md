# Detection of Text with Depressive Tendency Based on Data from Twitter
**by Wanqi Hu, Xinran Wang**

*names by the alphabetical order of the last names*

## Introduction

  Currently, Major depressive disorder (MDD) is among the most common mental illnesses. Individuals have resorted to expressing their emotional feelings on social media
resulting in several depressive sentiment messages on Twitter. The paper analyses four models with natural language processing techniques for the detection of depressive tendency of tweets; these models include: 
* SVM with Tf-Idf statistics
* Naive Bayes with Tf-Idf statistics
* LSTM with word2Vec statistics
* BERT model

Over 16000 data are used for training the models, while over 4000 data consisting of regular and depressive tweets are used for testing. Data associates Naive Bayes with Tf-Idf statistics with the least running time and the BERT model with the highest accuracy. 

*Index Terms: Major depressive disorder, Twitter, Tf-Idf, Word2Vec, LSTM, BERT*

## Flow of Model

* SVM/NB based on Tf-Idf statistics ![tfidf](https://github.com/Wanqi9Hu/Detection-of-Text-with-Depressive-Tendency-Based-on-Data-from-Twitter/blob/main/Flow/tfidf_flow.png)
* LSTM based on Word2Vec statistics ![lstm](https://github.com/Wanqi9Hu/Detection-of-Text-with-Depressive-Tendency-Based-on-Data-from-Twitter/blob/main/Flow/word2vec%2Blstm_flow_new.png)
* BERT ![Bert](https://github.com/Wanqi9Hu/Detection-of-Text-with-Depressive-Tendency-Based-on-Data-from-Twitter/blob/main/Flow/bert_flow.png)
