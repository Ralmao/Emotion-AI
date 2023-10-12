# Emotion-AI
Model  

The model is a ResNet 18, which is a convolutional neural network (CNN) that has been shown to be effective for image classification tasks. The model is trained on a dataset of facial images with corresponding emotion labels.The dataset includes images of people expressing a variety of emotions, such as happiness, sadness, anger, Hate and Surprise.

Training

The model is trained using the TensorFlow framework. The training process involves feeding the model a set of images and their corresponding emotion labels. The model then learns to associate the features of each image with the correct emotion label.

Deployment

The trained model is deployed on the TensorFlow server. This allows the model to be used to predict the emotions of new facial images.

Steps

Here are the steps involved in creating and deploying the model:

Install TensorFlow and Keras. TensorFlow is a machine learning framework that can be used to train and deploy neural networks. Keras is a high-level API for TensorFlow that makes it easier to build and train neural networks.
Download the dataset. The dataset of facial images with corresponding emotion labels can be downloaded from the Kaggle website: https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data.
Preprocess the data. The data needs to be preprocessed before it can be used to train the model. This involves resizing the images to a standard size and normalizing the pixel values.
Build the model. The model is built using the TensorFlow and Keras APIs. The ResNet 18 architecture is used as a starting point.
Train the model. The model is trained using the TensorFlow training API. The training process can take several hours, depending on the size of the dataset and the computing resources available.
Deploy the model. The trained model is deployed on the TensorFlow server. This can be done using the TensorFlow serving API.

Conclusion

The model presented in this document is a powerful tool for detecting emotions in facial images. The model is trained on a large dataset of facial images with corresponding emotion labels. The model is deployed on the TensorFlow server, which allows it to be used to predict the emotions of new facial images.
