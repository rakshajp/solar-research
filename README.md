# solar-research
Includes all research documentation for identifying solar panel installations in the Chicagoland area

## Dataset for Proof of Concept: 
### Dowloaded from: https://www.kaggle.com/competitions/ids705sp2020/data
https://drive.google.com/drive/folders/1v60pRPzJK6oglKXmirRJQfPxjkR1YtVj?usp=sharing

## Steps

### Data Collection: 

We are using a processed dataset sourced from https://www.kaggle.com/competitions/ids705sp2020/data

### Data Labeling: 

In a generated dataset, we would manually label a subset of the images, identifying which contain solar panels and which do not. This labeled dataset will be used to train the machine learning model. Here, the dataset we are using is already processed and labelled.

### Model Selection and Training: 

Train chosen model on the labeled dataset.
We must choose a suitable machine learning model- we compare and see that aconvolutional neural network (CNN), a type of deep learning model is effective for image analysis. 

### Model Evaluation: 

Evaluate the model's performance using a separate validation dataset. Adjust the model's parameters as necessary to improve its accuracy.

### Prediction: 

Use the trained model to analyze the remaining unlabeled images and predict the presence of solar panels.

### Post-Processing:

Analyze the model's predictions to extract useful information, such as the number and distribution of solar panels.

### Continuous Learning: 

As more labeled data becomes available, retrain the model to improve its accuracy.

