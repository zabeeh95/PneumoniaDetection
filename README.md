**📘 Pneumonia Detection from Chest X-Ray Images**

An end-to-end deep learning project for detecting Pneumonia from chest X-ray images using convolutional neural
networks (CNNs) and transfer learning. This repository contains training notebooks that explore multiple frameworks (
TensorFlow and PyTorch) for building robust image classifiers.
🧠 Project Overview

Pneumonia is a respiratory infection that can be diagnosed using chest X-ray images. This project demonstrates how deep
learning models can automate this classification task by learning distinctive visual patterns between healthy and
pneumonia-affected lungs.

**Key goals:**

Preprocess and analyse chest X-ray dataset

Train and evaluate deep learning models

Compare TensorFlow and PyTorch implementations

Use transfer learning for improved performance

**🛠 Core Features**
🧪 Training Notebooks

TransferLearning.ipynb – Uses pretrained models on chest X-ray data to leverage learned image features.

classifier_TF.ipynb – Builds and trains a CNN classifier using TensorFlow/Keras.

classifier_Torch.ipynb – Implements a CNN in PyTorch for the same task.

Each notebook includes:

Data loading and preprocessing

Model architecture

Training loops

Evaluation metrics (accuracy, loss, confusion matrices)

Visualization of training and evaluation results

**📦 Dataset**

This project uses a publicly available Chest X-Ray Pneumonia dataset structured into train, val, and test folders with
subfolders for:

NORMAL (healthy lung X-rays)

PNEUMONIA (lung X-rays showing pneumonia)

You can download the dataset from Kaggle and place it accordingly before training.

**🧑‍🔬 Model Evaluation**

After training, models are evaluated using key performance metrics such as:

Accuracy

Precision & Recall

Loss curves

Confusion matrices

These help assess robustness and practical performance on unseen held-out data.

**📈 Results**

Each notebook includes visual summaries of training behavior and model performance, enabling comparison between
approaches and insights into which technique is most effective for the task.
