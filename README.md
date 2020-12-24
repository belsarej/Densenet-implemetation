# Densenet-implemetation
We used CIFAR-10 dataset for our experiments with DenseNet Architecture.

Hyper Parameters:

Batch Size - 32,64,128,

Epoch - 20,30,40,50,70

Optimizer - ADAM , SGD (with & without momentum and weight decay)

Transformation - Rotation_Range = 30 , Horizontal Flip , Normalization by mean and Std Dev

Results

Accuracy  : 90.14


DenseNet-BC(k=12,L=100)

The No of Parameters in this Model is around 0.8 M which makes it easy to train and requires lesser computational power

This repo consists of:


Different Data Augmentation we used in our experiments in data augmentation.ipynb 

DenseNet Exp Excel file has the Expermentitonal Results

Final_DenseNet_implemntation.ipynb is the final model

check our densenet deployment here https://github.com/belsarej/DenseNet_deployment
