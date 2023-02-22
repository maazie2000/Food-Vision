
# Food Vision 🍔👁️

![image](https://user-images.githubusercontent.com/73777608/220505155-b69caab3-a6b6-459b-a19c-fd0ef5cbb174.png)


This project is based on the Development of a model that can take in food images, and identify them. This repository is part of Milestone Project 1 for the Zero to Mastery Tensorflow Course 

## Modeling Experiments

Only 1 model will be created and improved throughout the notebook. This model uses a pretrained model known as `EfficientNetB0`. The model is something similar to the following :-   

`Input Layer`  -> `EfficientNetB0` -> `Global Average Pooling Layer` - > `Dense Layer`

## Datasets
The dataset used in this notebook is the `food101` dataset, that has 101 different classes of food. The dataset can be loaded using tensorflow datasets. 

## Evaluation
The model has been uploaded to tensorboard to visualize how good the model performed. The model didn't achieve target accuracy, but soon will 😤.

## Course Acknowledgements
Thanks you Daniel Bourke and Andrei Neagoie for this amazing course! I really loved it and look forward to doing the NLP section!

