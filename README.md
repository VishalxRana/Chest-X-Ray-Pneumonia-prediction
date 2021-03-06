# Chest X-ray Pneumonia Predicion
This project was made with Transfer Learning method, using VGG 16 model. The project's dataset was found on [kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). The data was provided into 3 folders, viz. train, test and val. 

The project was to classify whether the patient has pneumonia or not. The data folders were subdivided into two folders of NORMAL & PNEUMONIA. 

## Visualizing the data 
Here is the image of a NORMAL patient's chest X-ray and a PNEUMONIA patient's chest X-ray. 
Left side is a NORMAL patient's x-ray and right side is of PNEUMONIA patient's x-ray. 

![Chest X-ray visualized](https://github.com/VishalxRana/Chest-X-Ray-Pneumonia-prediction/blob/main/Images/train_data.png)

## Visualizing augmented images
We have augmented the images from the original data, like flipping them, shearing them, rotating them upto a certain degree, etc. in order to increase the data slightly. This will add modified images to the dataset as well. 
Left side is a Original Image and the right side is the augmented image.

![Augmented data visualized](https://github.com/VishalxRana/Chest-X-Ray-Pneumonia-prediction/blob/main/Images/augmented_image.png)

# Conclusion 
Testing the model on the validation data provided in the dataset, it predicted **87%** accurately.  