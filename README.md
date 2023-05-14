# Covid_detection

## Introduction:
The COVID-19 pandemic has had a significant impact on the world, with millions of people affected globally. One of the crucial steps to prevent the spread of COVID-19 is early detection and isolation of infected individuals. With the help of machine learning, we can develop models that can aid in the early detection of COVID-19.

## Dataset:
I used a publicly available dataset consisting of chest X-ray images of COVID-19 positive patients and normal individuals. The dataset was divided into two classes: COVID and Normal.
- https://drive.google.com/drive/folders/10wf4C61de-hHwbIlvVtzcQTheQgKvfMP?usp=sharing

## Model Architecture:
I used the VGG16 base model with a sequential model for COVID detection. The VGG16 model is a convolutional neural network that is well suited for image classification tasks. We added two fully connected layers to the VGG16 model to make predictions for the two classes: COVID and Normal. We trained the model for 25 epochs.
<br
    
<img src="https://github.com/atisamhaq123/Covid_detection/blob/main/images/3.png" style="height: 500px;width:auto">

## Model Performance:
After training the model, it achieved a training accuracy of 97.9%. We evaluated the model using a classification report and obtained the following results

## Accuracy
<img src="https://github.com/atisamhaq123/Covid_detection/blob/main/images/1.png" style="height: 500px;width:600px">

## Loss
<img src="https://github.com/atisamhaq123/Covid_detection/blob/main/images/2.png" style="height: 250px;width:600px">
<br>

## Conclusion:
Using machine learning, we developed a model that can aid in the early detection of COVID-19. The model achieved high accuracy and precision, making it a promising tool for healthcare professionals to detect COVID-19 cases early. However, this model should not replace diagnostic testing by a healthcare professional, and further research is needed to validate the model's performance on larger datasets and in different clinical settings.

