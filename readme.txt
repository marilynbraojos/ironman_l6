In this approach, we leveraged the VGG16 pre-trained CNN to achieve the image classification task. The file structure is the following: 
2025S_imgs: contains all images provided consolidated in a single folder. This was leveraged to expand the dataset used in training with img_rename.ipynb to help with this. 

Training the model: 
The model was trained in train_model. Some data pre-processing techniques employed were rotation, color jitter, resizing to confirm to VGG, and pixel normalization. 

The model was saved as a pkl file and integrated into model_grader. 

During training, the following best accuracy was achieved: 95.59%
During testing on 20% of the dataset, the following accuracy was achieved: 93.86%

This file can be run by running each line of the .ipynb file. 