# Emotion-Detection-model
This is a project that builds a emotion detection TensorFlow Lite  model

------------------------------------------------------------------------------
Documentation for the Built Model:
------------------------------------------------------------------------------
The model is built on the "FER-2013" dataset after data pre-processing
we are left with a total of 9308 images for traing.

The model was built primarily using the Tensorflow package.
------------------------------------------------------------------------------
All the requierd packeges are as follows.

        tensorflow - pip install tensorflow.
        
        OpenCV - pip install opencv-contrib-python

        Matplotlib - pip3 install matplotlib

        Numpy - pip instll numpy
------------------------------------------------------------------------------
The model is built using "Transfer Learing" technique. In which we use a 
pre-built model to create a desierd new model by adding our own layers.

The pre-built model used here is called "MobileNetV2" which is a well 
known model in Tensorflow, it has 53 layers in total and is a CCN model.

Our new model adds few layers to MobileNetV2 and the total number of
layers comes up to 57.

The model gives us a accuracy of 92.02% on the FER-2013 dataset.
