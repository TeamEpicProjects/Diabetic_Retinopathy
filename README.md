# Diabetic_Retinopathy
Developed a model using Convolutional Neural Network which allows a diabetic patient to upload their retina scan image and identify the probable stage of their Diabetic Retinopathy condition(No_DR, Mild, Moderate, Severe, Proliferative). Achieved 80% accuracy with minimal difference in training loss and validation loss.

Here's the link to the dataset:
https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data/data

The model takes 250 images in total as input, 50 from each category of Diabetic Retinopathy stages. 
The data has been sliced due to the heavy computation that is needed in order to run the model.
Several data augmentation techniques have been applied to the model to achieve the best results.



The images consist of retina scan images to detect diabetic retinopathy. The original dataset is available at APTOS 2019 Blindness Detection. These images are resized into 224x224 pixels so that they can be readily used with many pre-trained deep learning models.
All of the images are already saved into their respective folders according to the severity/stage of diabetic retinopathy using the train.csv file in the link provided. You will find five directories with the respective images:

0 - No_DR
1 - Mild
2 - Moderate
3 - Severe
4 - Proliferate_DR
