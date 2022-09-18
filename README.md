# Machine-Learning Algorithms for Automated Identification of Two-Dimensional Materials 
Here we have implemented physically informed tree-based methods and Convolutional Neural Networks (CNNs) for the rapid 
identification of optical images which contain or do not contain flakes. 
The project is organized into the directories: 
- CNN
- Evaluation
- Tree Methods 
- util

## CNN
Contains all code used to augment the data, construct the CNNs, and determine their accuracy.

## Evaluation
In evaluation, the Gradient-weighted Class Activation Mapping (Grad-CAM) images, which display where the CNNs train and test, are investigated.
We use a masking algorithm to determine the amount of overlap between the Grad-CAM heatmap of correctly classified images with 
flakes and the actual flake. 

## Tree Methods
Here all the features of the tree-based methods (decision tree, gradient boosted decision tree, and random forest) are 
constructed. We also optimize the hyperparameters of each method with a grid search 5-fold cross-validation and display visualizations
of the decision tree's decision process. 

## util 
Manual classification of all initial images for training and testing.
