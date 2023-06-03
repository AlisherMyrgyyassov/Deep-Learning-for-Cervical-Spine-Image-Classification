# Deep-Learning-for-Cervical-Spine-Image-Classification

**The dataset used:**

https://www.kaggle.com/datasets/saberghaderi/rsna-cervical-spine-train-image-png-csfd

![image](https://github.com/AlisherMyrgyyassov/Deep-Learning-for-Cervical-Spine-Image-Classification/assets/79082361/09029c8f-67dc-438c-9060-6f997f168597)

**About Dataset:**

This dataset with 20473 training image in 58 folders was randomly collected from cervical spine fracture detection images.
All photos are in png format.
The CT scan machine prepares multiple images of different cross-sections in a spiral form. The images in each folder are the result of one imaging stage.
I further preprocessed the dataset by normalizing the values.

**Model used:**

U-Net Neural Network 

**About This Project: **

The U-Net model was trained on the randomly selected 80% of the dataset and tested on the rest 20%. The model is trained to classify the input image and return a tensor with 63 channels, where each channel is a class. The model could achieve a decent performance of 92% correctly classified images. The model checkpoints are also uploaded in this repo.
