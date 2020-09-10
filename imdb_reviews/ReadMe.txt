This folder involves the prediction of IMDB movie review as positive or negative.
I have used LSTM(long short term memory) model to perform this sentiment analysis.
Code can split into three parts:
1) Data preprocessing:
  (a) Removing stop words from sentences.
  (b) Word embedding: Used one hot encoding to convert words to integers.
  
2) Model design:
   Model consisted of :
   (a) Embedding layer
   (b) LSTM layer with 200 nodes
   (c) Dropout layer with probability of 0.2
   (d) LSTM layer with 100 nodes
   (e) Dropout layer with probability of 0.2
   (f) LSTM layer with 50 nodes
   (g) Dense layer with one node as the output layer.
   
 3) Model is compiled with Adam optimizer, binary cross entropy as the loss function and accuracy as metrics.
