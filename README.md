# Eye For Blind - ImageCaption

# **Problem Statement**

Create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library.  

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by a CNN-based encoder and this will be decoded by an RNN model.

**The project is an extended application of** [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper](https://arxiv.org/abs/1502.03044). 

The dataset is taken from the [Kaggle website](https://www.kaggle.com/adityajn105/flickr8k) and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

# Solution Pipeline for Capstone Project
There are four major stages in this solution as described below: <br><br>
1) **Dataset creation**

![Pipeline1.JPG](attachment:Pipeline1.JPG)


2. **Model Building**

![Pipeline2.JPG](attachment:Pipeline2.JPG)

3. **Model Training**

![Pipeline3.JPG](attachment:Pipeline3.JPG)

4. **Model Evaluation**

![Pipeline4.JPG](attachment:Pipeline4.JPG)

# Solution Architecture

![Solution_Architecture.JPG](attachment:Solution_Architecture.JPG")
