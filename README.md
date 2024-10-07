# Image Classification on CIFAR-10
### Neural Networks and Deep Learning Lab ECE NTUA 2023-2024

## Creator

 **Afroditi Marianthi Chlapani [github](https://github.com/ntua-el20889)** 

---

## Project Overview

This project implements an **Image Classification system** using **Wide Residual Networks** to classify images from the **CIFAR-10** dataset. The goal of the project is to build an effective image classifier by experimenting with different architectures and applying advanced data augmentation techniques.

Key features:
- **Model Architecture Experimentation**: Implementing various configurations of Wide Residual Networks by modifying their depth and width to observe their impact on classification accuracy.
- **Advanced Data Augmentation**: Utilizing the MixUp technique to create synthetic images and enhance the training dataset, leading to improved model generalization.
- **Performance Evaluation**: Assessing the model's accuracy and training time on both training and testing sets, ensuring reliable evaluation metrics.
- **Dropout Regularization**: Implementing dropout layers to prevent overfitting and improve model performance.

---

# Contents

- [Prerequisites](#Prerequisites)
- [How to Set Up and Run](#How-to-Set-Up-and-Run)
- [Results](#Results)
- [Contributing](#Contributing)

## Prerequisites

To run this project, you will need:

- Python 3.x: [Download Python](https://www.python.org/downloads/)
- Required Python packages: Install the necessary packages using the following command:
  ```bash
  pip install -r requirements.txt
  ```

## How to Set Up and Run

### Clone the Repository
First, clone the repository to your local machine:
```bash
git clone https://github.com/your-github-profile/image-classification-cifar10.git
cd image-classification-cifar10
```

### Running the Application
To run the Jupyter Notebook, use the following command:
```bash
jupyter notebook ex1_template.ipynb
```
Follow the instructions in the notebook to execute the code and evaluate the model.

## Results
After training the models, you can find the evaluation results in the notebook. The metrics to look for include:
- **Accuracy** on the test set
- **Training time**

