# TensorFlow_Image_Classification_using_ResNEtV2_on_CIFAR

TensorFlow image classification using CIFAR using a ResNetV2 based encoder.

This configuration achieves 93.0% accuracy in 60 epochs with each epoch taking ~ 50s on Google Colab.  

Accuracy can be improved via
  1) Improved training data augmentation
  2) Improved network design
  3) Improved network training
  
  
  Examples (currently commented out) are included for the following
  1) Computing the dataset mean and std dev
  2) Restarting training after a crash from the last saved checkpoint
  3) Saving and loading the model in Keras H5 format
  4) Saving and loading the model in TensorFlow SavedModel format
  5) Getting a list of all feature maps
  6) Creating an encoder only model
