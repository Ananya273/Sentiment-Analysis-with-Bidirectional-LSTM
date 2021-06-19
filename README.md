# Sentiment-Analysis-with-Bidirectional-LSTM

Sentiment analysis has received extensive
attention in the NLP domain due to its wide range of applications. The valuable features obtained from
sentimental analysis can be used in a broad range of applications,
such as opinion detection, political promotion and
decision making. The most common and existent methods used have been quite ineffective as they are insensitive to contextual information and fail to handle the long distance dependencies in words. 

- To overcome these challenges, in this project a `word2vec` model is incorporated to capture semantic features of words and convert them into high dimentional word vectors (embeddings). 
- Word embedding techniques based on neural networks can
overcome the difficulties of traditional word representation methods as they can encode the semantic and syntactic properties of words to provide relatively precise information for document representation. This is done using the `Continuous Bag-of-Words (CBOW)` method.

- After that Stacked Bi-directional Long Short Term Memory (Stacked Bi-LSTM) model utilizes sequential word vectors transformed from CBOW model to represenet contextual features. Lastly a binary `softmax classifier` extracts information from the last hidden layer to predict the sentiment orientation by using semantic features. 
-  `Cross Entropy` is used to find the difference between predicted and real values and calculate loss for each statement. Based on the loss values, `adam optimiser` is used for optimising the paramters.

![image](https://user-images.githubusercontent.com/7736847/122645952-9d29c200-d13a-11eb-87e3-58212f443b5a.png)

