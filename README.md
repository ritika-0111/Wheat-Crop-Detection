# Wheat-Crop-Detection  
The dataset used is Global Wheat Detection.We can find this dataset here: https://www.kaggle.com/c/global-wheat-detection  
The data is images of wheat fields, with bounding boxes for each identified wheat head.Each image is of 1024 * 1024 
Note: Not all images include wheat heads / bounding boxes.  
It includes:  
 train.csv - the training data  
 train.zip - training images  
 test.zip - test images  
   
*train.csv* consists of four columns:  
image_id - unique image ID  
width - 1024  
height - 1024  
bbox - a bounding box, formatted as a Python-style list of [xmin, ymin, width, height]  
source - source of image  
Note: There are 7 sources of data: ['usask_1' 'arvalis_1' 'inrae_1' 'ethz_1' 'arvalis_3' 'rres_1' 'arvalis_2']
