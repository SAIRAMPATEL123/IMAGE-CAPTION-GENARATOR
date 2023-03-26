# image-caption-generator
Image caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). 


Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision. 

It includes the labeling of an image with English keywords with the help of datasets provided during model training.
flickr 8k dataset is used to train the CNN model called Xception. Xception is responsible for image feature extraction.
These extracted features will be fed to the LSTM model which in turn generates the image caption.

The primary goal of this project is to develop a model for generating accurate captions for various images without depending on the clarity of the image.
This model will generate precise captions and will reduce the error rate. This model will be able to generate captions even though the image is unclear.
