# Deep_Learning_Eye_for_the_blind

**The dataset has been downloaded from the following link:** https://www.kaggle.com/adityajn105/flickr8k

It consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

In this capstone project, we need to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset.This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

**Project Pipeline:**
  1. Data Understanding: Here, we loaded the data and understood the representation.
  2. Data Preprocessing: In this step, we have processed both images and captions to the desired format.
  3. Train-Test Split: Combined both images and captions to create the train and test dataset.
  4. Model Building: This is the stage where we have created our image captioning model by building Encoder, Attention and Decoder model.
  5. Model Evaluation: Evaluated the models using BLEU score.
