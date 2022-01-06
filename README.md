# UAV-image-classification-by-CNN
This code if for classifying remote senisng UAV images collected from vineyards using a convolutional neural network (CNN).

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
 
 
 
