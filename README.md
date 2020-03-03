# Face-Detection

Project Description - Face Detection
Project Description
In this hands-on project, the goal is to build a face detection model which includes building a
face detector to locate the position of a face in an image.

Dataset: WIDER Face Dataset
WIDER FACE dataset is a face detection benchmark dataset, of which images are selected
from the publicly available WIDER dataset.
This data has 32,203 images and 393,703 faces are labelled with a high degree of variability in
scale, pose and occlusion as depicted in the sample images.
In this project, we are using 500 images and 1100 faces for ease of computation.
We will be using transfer learning on an already trained model to build our detector. We will
perform transfer learning on Mobile Net model which is already trained to perform object
detection. We will need to train the last 6-7 layers and freeze the remaining layers to train the
model for face detection. To be able to train the Mobile Net model for face detection, we will be
using WIDER FACE dataset which already has the bounding box data for various images with a
single face and multiple faces. The output of the model is the bounding box data which gives the
location of the face in an image. We learn to build a face detection model using Keras supported
by Tensorflow.

Data link : 
https://drive.google.com/file/d/1rolp8QqyKkvxJwlBAPPGtG2f3JA7hMwk/view?usp=sharing

Overview
In this problem, we use "Transfer Learning" of an Object Detector model to detect any object
according to the problem in hand.
Here, we are particularly interested in detecting faces in a given image. Below are the steps
involved in the project.
1. Load the dataset given in form .npy format.
2. Create Features(images) and labels(mask) using that data.
3. Load the pre-trained model and weights.
4. Create model using the above model.
5. Define Dice Coefficient and Loss function.
6. Compile and fit the model.
7. Evaluate the model.
