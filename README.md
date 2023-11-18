Solar Panel Surface Classifier
Overview
This project aims to classify various surface conditions of solar panels using deep learning models. The models are trained to identify and classify different states such as clean, dusty, bird-dropped, electrical damage, physical damage, and snow-covered surfaces on solar panels.

Data Source: https://www.kaggle.com/datasets/pythonafroz/solar-panel-images

image

Models and Results
The project experimented with three different deep learning architectures:

DenseNet121
EfficientNetB0
VGG
Each model was trained and evaluated on the dataset, achieving the following results:

- DenseNet121:
image image image image

- EfficientNetB0:
image image image image

- VGG:
image image image image

The comparison indicates that DenseNet121 performed slightly better than the other models in accurately classifying various surface conditions.

Dataset and Classes
The dataset used in this project consists of images scraped from the internet. It includes six different classes:

Clean
Dusty
Bird-drop
Electrical Damage
Physical Damage
Snow-covered
Usage and Installation
To use this project, follow these steps:

Clone the repository.
Install the necessary dependencies.
Run the model training script.
Conclusion and Recommendations
The developed model showcases promising accuracy in classifying surface conditions of solar panels. Further improvements could involve data augmentation techniques and fine-tuning hyperparameters to enhance the model's robustness and generalization.
