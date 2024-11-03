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

## Security
Here, we got a trained model with a backdoor attack on MNIST dataset. We use Neural Cleanse[1] in order to first identify the trigger for attack and the affected class and then reconstruct the trigger pattern and finally using unlearning method for cleansing the attack from the model.

## Fairness
In this code we first try to implement a classifier and which have a high accuracy. But the problem is this classifier is not fair toward different genders (We measure fairness here with Zemel Fairness and Disparate Impact). We try to change the training data in a way in which after learning we have acceptable and high accuracy but also the model is fair toward both men and women.


[1] Bolun Wang, Yuanshun Yao, Shawn Shan, Huiying Li, Bimal Viswanath, Haitao Zheng, and Ben Y Zhao. Neural cleanse: Identifying and mitigating backdoor attacks in neural networks. In Proceedings of 40th IEEE Symposium on Security and Privacy, 2019
