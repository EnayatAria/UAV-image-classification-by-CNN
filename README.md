# UAV-image-classification-by-CNN

# Code 1: CNN_vineyard

This code if for classifying remote senisng images using a convolutional neural network (CNN).
It is applied to UAV images collected from vineyards in southern regions in France.

The code is implemented in google colab.

It needs CUDA for paralled processing (Go to 'Runtime' in Google colab --> change runtime type ---> Hardware accelerator ---> GPU  ).

Inputs:

 -  Input image file in envi format. 
It reads the image file form a specfied address from Google drive: in 'DataPath'
 -  trianing dataset: in textPath.
 The trianing dataset is in ASCII format created by saving the ROI(region of intertest) of ENVI to ASCII file
 
 Outputs:
 - Trained network for later classification of similar images: savepath
 - Classification map of the given image in ENVI format 
 
 # Code 1: CNN_vineyard_trained
 
 This code gets a tranied CNN for vineyards classification based on UAV images with spatial resolution of 10 cm and and % spectral bands.
 
 Inputs:
 - RS images corresponde to the images that the network already classified based on that.
 - Tranied CNN with .pkl format (the trianed CNN is also in the repository: net_params_2DCNN2.pkl)
 
 Outputs:
 -  Classification map of the given image in ENVI format 
 
 
 

 
