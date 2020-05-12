## DESCRIPTION
- Self driving a car is a project to enable the car run by a program without the of human intervention. 
## TECHNOLOGIES 
 - OpenCV
 - TensorFlow
 ## OBJECTIVES
 - Process the images to find the angles to deviate
 - Minimize error
 ## DATA FORMAT
 - Total number of images -45406
 - Angle label for each image
 ## EXPLORATORY DATA ANALYSIS
  - Load data using OpenCV
  - Train test split (70 :30)
  ## MACHINE LEARNING MODEL : Base line Model
  
  ### Configuration
   - Train test (70 : 30)
   - Dropout : 0.50
   - AdamOptimezer Value: 1e-3
   - Activation Function: linear
   
## How to Use
A TensorFlow implementation of this [Nvidia paper](https://arxiv.org/pdf/1604.07316.pdf) with some changes.

Download the [dataset](https://drive.google.com/file/d/0B-KJCaaF7elleG1RbzVPZWV4Tlk/view?usp=sharing) and extract into the repository folder

Use `python train.py` to train the model

Use `python run.py` to run the model on a live webcam feed

Use `python run_dataset.py` to run the model on the dataset

To visualize training using Tensorboard use `tensorboard --logdir=./logs`, then open http://0.0.0.0:6006/ into your web browser.
