# Diabetic_Retinopathy
Developed a model using Convolutional Neural Network which allows a diabetic patient to upload their retina scan image and identify the probable stage of their Diabetic Retinopathy condition(No_DR, Mild, Moderate, Severe, Proliferative). Achieved 80% accuracy with minimal difference in training loss and validation loss.

Here's the link to the dataset:
https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data/data

The model takes 250 images in total as input, 50 from each category of Diabetic Retinopathy stages. 
The data has been sliced due to the heavy computation that is needed in order to run the model.
Several data augmentation techniques have been applied to the model to achieve the best results.
