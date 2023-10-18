# FakeNews-detection-LSTM
FakeNews Detection using LSTM deep learning algorithm
LSTM stands for Long Short Term Memory
steps invloved to create model for fakenews detection using LSTM
Step1:collect dataset from kaggle.com 
Step2: preprocess the data by cleaning the missing values and converting the text into numerical form by using "texts_to_sequences"
method and "Tokenizer" is used to split the text into individual tokens, "pad-sequences" is used to make all the numerical values has same length
step3: Training the  deep learning model by initializing "Sequential" function now started adding Layers
Embedding layer:' Create an embedding layer to convert the numerical word tokens into dense vectors. This layer helps the LSTM model understand the semantic meaning of words based on their context within the news articles.'
LSTM layer:'Use one or more LSTM layers to process the sequential information in the news articles. The LSTM layers capture dependencies and patterns in the text data.'
Dense Layers:' Add one or more dense layers to the model to perform the final classification. The last dense layer should have a single unit and a sigmoid activation function for binary classification (fake or real).'
now,fit the train data in the model and its display the accuracy and save our model into ".h5" model
Finally manual testing has done for our trained model and predict the output whether a given news is real or fake.
