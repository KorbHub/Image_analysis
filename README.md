# Image_analysis
Collection of my practice and project in the field of image processing and computer vision project

Project 1: Cancer detection using ensemble of convulutional neural network models 

This project tries to construct a deep learning model(based on a convolutional neural network) to identify metastatic tissue in histopathologic scans of lymph nodes.

I use transfer learning from a pre-trained model Xception and MObileNetV2. Then using the Global Average Pooling function on the result from each pre-train model, and then concatenate the pooled result for the final presentation.

The different combinations of the pre-trained model can be selected to find the most appropriate ensemble combination. 

The computational cost of this training is very high, so it should be run on the GPU or Kaggle notebook. 
