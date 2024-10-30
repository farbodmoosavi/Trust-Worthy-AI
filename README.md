# Trust-Worthy-AI
Projects of Trust-Worthy AI course by Prof. Tavassolipour in University of Tehran

## Generalization
This Folder contains codes related to generalization of a model that uses MNIST and SVHN datasets. In each file we compare different techniques and their effects on the genralization of the models. This files inculde the Base model, changing model architecture (for example usingg batch normalization, dropuot layers, etc.), different loss functions, using different data augmentation methods and combining them, using different input features, using diiferent optimizers for learning, and also fine tuning the models.

## Explainability
### Tabular Data
In this Section, using diabetes dataset, first we analyze data and classes and find correlation between features. Then we train a model and try to analyze its explainability and feature importance in its decision making using LIME (Local Interpretable Model-Agnostic Explanations) and Shapley methods.
### Image Classification
Here we analyze where in an image and different classes will the model have more importance using different methods including GRAD-CAM. Guided GRAD-CAM, and SmoothGrad. Then we try and test these by creating a attack to change the class of an input and again anylize saliency maps.
Another thing here is feature visualization in which we try to create meaningful images to maximize the output related to a certain class.
