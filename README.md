# Text-classification-using-CNN
Text classification is a classic topic for natural language processing, in which one needs to assign predefined categories to free-text documents.
Many researchers have found convolutional networks (ConvNets) are useful in extracting information from raw signals, ranging from computer vision applications to speech recognition and others. 

In this project, we applied convolutional networks to text classification. Our main objective is to classify the text. In this we intend to compare using 2 models. One is word-based ConvNet and the other is through LSTM.

We used the data set amazon reviews , which has several reviews about the amazon services given by their customers. It is a very huge data and has around 194439 reviews.
We have also used yelp data set which contains a JSON of nearly 5 million entries. we splitted this JSON for performance reason to randomly 600000 train and 200000 test documents.

  Accuracy 
  
  LSTM(Amazon) - 0.88  
  LSTM(yelp) - 0.8845   
  CNN(yelp) - 0.93
                      
 
 
 
 
