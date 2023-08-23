# Text_classification_with_Transformer
Code for building a Transformer model to perform Sentiment Analysis/classification on text data. The model combines a positional embedding layer with an encoder-type transformer and then a outputs through a feed forward linear layer.
The project is divided into: General understandng of Transformers, Data analysis and pre_processing,Model development(Training & Validation).
The model was built with keras and notable sub-modules include Layers and Callbacks,Data analysis libraries include pandas, numpy,TextVectorization from keras.layers and train_test_layers from sklearn.model_selection.
The dataset used for the training and evaluation of the model contains 600,000 text data grouped into either psoitive,negative or neutral
The project was run on GPU powered google colab notebook.
