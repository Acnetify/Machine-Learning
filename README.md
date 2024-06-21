# Machine-Learning

## Acnetify: Acne Identify
Acnetify is a machine learning project designed to classify different types of acne using a convolutional neural network (CNN). This project aims to provide an accurate and efficient way to identify acne types, assisting dermatologists and individuals in better understanding and managing acne.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Project Overview

Acnetify utilizes TensorFlow and TFLite to build and deploy a CNN model capable of classifying acne into five categories:
- Whitehead
- Papula/Pustula
- Milia
- Blackhead
- Acne Nodules

## Dataset
The model is trained on a dataset sourced from several resources such as Google, Kaggle, and Roboflow, with collaborative data science efforts managed through Deepnote and Google Colab. There are 120 training images and 30 testing images on each of the class, so in total, there are 750 images. We also perform several data augmentation techniques to generate more training data to improve generalization and prevent overfitting.

## Model Architecture

Acnetify leverages several CNN architectures, starting from custom model, ResNet50, ResNet101, ResNet152, MobileNet, with custom layers added for classification. The models are built using TensorFlow and trained with various data augmentation techniques to improve generalization.

## Usage
1. Prepare the dataset:
    - Place the dataset in the appropriate directory.

2. Train the model:
    - Open and run the provided Jupyter Notebook.
    - The notebook will guide you through data augmentation, model training, and evaluation.

3. Evaluate the model:
    - The notebook includes steps to evaluate the model using the test set and visualize the results.

## Results

The trained models achieve high accuracy in classifying the different types of acne. Detailed results and performance metrics, including accuracy, confusion matrices, and classification reports, will be generated and displayed within the Notebook.

## Contributing

We welcome contributions to the Acnetify project. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add new feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Open a pull request.


## Acknowledgements

- [Kaggle](https://www.kaggle.com/)
- [Roboflow](https://roboflow.com/)
- [Deepnote](https://deepnote.com/)
- [Google Colab](https://colab.research.google.com/)
- [TensorFlow](https://www.tensorflow.org/)
