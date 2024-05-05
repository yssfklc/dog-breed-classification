# End-to-End Multiclass Dog Breed Classification

This Jupyter Notebook demonstrates how to build an end-to-end multiclass image classifier for dog breed identification using TensorFlow 2.0 and TensorFlow Hub.

## 1. Problem Statement

The goal is to develop a model that can automatically identify the breed of a dog given an image.

**Motivating Scenario:**
Imagine you're at a cafe and see a curious pup. By taking a picture and running it through this model, you could instantly identify the breed!

## 2. Dataset

The training data is sourced from Kaggle's dog breed identification competition [link to Kaggle dataset](https://www.kaggle.com/c/dog-breed-identification/data). This dataset consists of over 10,000 labeled images representing various dog breeds.

## 3. Evaluation Strategy

The model's performance will be evaluated based on its ability to predict breed probabilities for each image in a separate test set (also containing over 10,000 images). These test images lack labels, allowing us to assess the model's generalization capability.

## 4. Feature Engineering Considerations

Since we're dealing with unstructured image data, deep learning or transfer learning techniques are well-suited for this task. The training set provides a significant amount of data (around 10,000+ images), which can be leveraged effectively by deep learning models.

![image](https://github.com/yssfklc/dog-breed-classification/assets/121329421/d296b4ac-eb75-44a3-8bbd-8e9fe6a27ba9)

