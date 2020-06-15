# deeplearning
Deep Learning Code
# Develop an image caption generator model using Tensorflow-keras

In this code, we will have to train a caption generator model for images. It requires a CNN model to
extract the content of images and an RNN model to learn the corresponding captions of the images. These two
features are finally merged and trained using dense layers.

This notebook is divided into six parts. 
1. Download photo and caption dataset 
2. Prepare photo data 
3. Prepare text data 
4. Develop deep learning model with progressive data loading 
5. Evaluate model 
6. Generate new captions 


The below research papers are for reference-
1. Where to put the Image in an Image Caption Generator (https://arxiv.org/abs/1703.09137)
2. Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics
(https://www.ijcai.org/Proceedings/15/Papers/593.pdf)


#MNIST image processing - Model evaluation code is also included as seperate file
