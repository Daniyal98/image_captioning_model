# Image Captioning Model

Trained an image captioning model on my computer that generates a one line caption for an image. The model consists of two parts. One is an encoder that is a convolutional neural network that extracts features from the image. The second part is a decoder that is a recurrent neural network that generates a one line caption for the features. The decoder uses the features extracted the encoder as input.

## Dataset

This model uses COCO 2017 dataset that can be downloaded from this link https://www.kaggle.com/datasets/awsaf49/coco-2017-dataset?resource=download.