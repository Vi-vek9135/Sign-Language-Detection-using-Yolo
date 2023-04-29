This repository contains the implementation of a deep learning model for detecting and recognizing signs using computer vision. The model is built using the TensorFlow framework and is based on the YOLO (You Only Look Once) architecture.


Installation
To run the code in this repository, you will need to have Python 3.6 or higher installed on your system. You will also need to install TensorFlow, OpenCV, and other required libraries.


Step :  1
Capture your images by running capture_images.py

Step : 2
Label all images using annotation tool 

Step : 3
Create one folder naming Data
In Data folder ,Create two folders and one file i) train , ii) test  and download or create data.yml

Step : 4
In train and test folders , create two folders naming images and labels

Step : 5
In train/images folder paste all images that you have captured. And in train/labels paste all labeled images 

Step : 6
In test/images folder paste 20%-30% of  images that you have captured. And in train/labels paste 20%-30% of labeled images 

Step : 7
Upload train folder , test folder and data.yml file in google colab

Step : 8
Finally run all the cells of google colab file one by one

Note : For better results increase the epoch number ( approx. 300 to 400 )

If you have any problem then contact me at vikash46719@gmail.com
