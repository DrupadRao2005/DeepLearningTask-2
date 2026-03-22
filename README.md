# Deep Learning Assignment – CNN, RNN, LSTM, GRU, GAN
## Applied Deep Learning Models

This repository contains the implementation of multiple deep learning models as part of the Deep Learning course assignment. All models were implemented and executed in a single Jupyter Notebook file.

The project includes implementation of:
- Convolutional Neural Network (CNN)
- Transfer Learning Model
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Generative Adversarial Network (GAN)

The models were applied to different tasks such as image classification, text classification, and image generation.

---

# Project Objectives

The main objective of this assignment is to implement and analyze different deep learning architectures and compare their performance across different types of machine learning problems.

The project includes:
1. Image classification using CNN
2. Image classification using Transfer Learning
3. Text classification using RNN, LSTM, and GRU
4. Image generation using GAN
5. Performance comparison using accuracy and loss curves
6. Confusion matrix for classification model
7. Generated images from GAN at different epochs

---

# Datasets Used

## Fashion-MNIST Dataset
Used for:
- CNN Image Classification
- Transfer Learning
- GAN Image Generation

Dataset details:
- 70,000 grayscale images
- 10 classes
- Image size: 28 × 28
- Training samples: 60,000
- Testing samples: 10,000

## IMDB Movie Reviews Dataset
Used for:
- RNN
- LSTM
- GRU text classification

Dataset details:
- 50,000 movie reviews
- Positive and Negative sentiment classification
- Vocabulary size: 10,000
- Sequence length: 200

---

# File Structure

This project uses a single notebook for all models.
# Deep Learning Assignment – CNN, RNN, LSTM, GRU, GAN
## Applied Deep Learning Models

This repository contains the implementation of multiple deep learning models as part of the Deep Learning course assignment. All models were implemented and executed in a single Jupyter Notebook file.

The project includes implementation of:
- Convolutional Neural Network (CNN)
- Transfer Learning Model
- Recurrent Neural Network (RNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Generative Adversarial Network (GAN)

The models were applied to different tasks such as image classification, text classification, and image generation.

---

# Project Objectives

The main objective of this assignment is to implement and analyze different deep learning architectures and compare their performance across different types of machine learning problems.

The project includes:
1. Image classification using CNN
2. Image classification using Transfer Learning
3. Text classification using RNN, LSTM, and GRU
4. Image generation using GAN
5. Performance comparison using accuracy and loss curves
6. Confusion matrix for classification model
7. Generated images from GAN at different epochs

---

# Datasets Used

## Fashion-MNIST Dataset
Used for:
- CNN Image Classification
- Transfer Learning
- GAN Image Generation

Dataset details:
- 70,000 grayscale images
- 10 classes
- Image size: 28 × 28
- Training samples: 60,000
- Testing samples: 10,000

## IMDB Movie Reviews Dataset
Used for:
- RNN
- LSTM
- GRU text classification

Dataset details:
- 50,000 movie reviews
- Positive and Negative sentiment classification
- Vocabulary size: 10,000
- Sequence length: 200

---

# File Structure

This project uses a single notebook for all models.


---

# Requirements

Install the following libraries before running the notebook:


2. Run the cells in order from top to bottom.

3. The notebook contains the following sections:
- CNN Model Training
- Transfer Learning Model
- RNN Model
- LSTM Model
- GRU Model
- GAN Model Training
- Graph Generation
- Confusion Matrix
- Generated Images

4. The models will automatically download datasets and train.

5. The following outputs will be generated:
- Accuracy curves
- Loss curves
- Confusion matrix
- GAN generated images
- GAN loss graph

---

# Models Implemented

## CNN Model
Used for image classification on Fashion-MNIST dataset. The CNN architecture includes convolution layers, pooling layers, dropout, and dense layers.

## Transfer Learning Model
A pretrained model was used for transfer learning to improve classification accuracy.

## RNN, LSTM, GRU Models
These models were used for text classification using the IMDB movie reviews dataset. Their performance was compared using accuracy and loss curves.

## GAN Model
A Generative Adversarial Network was implemented to generate Fashion-MNIST images. The generator and discriminator were trained alternately. Images were saved at different epochs to observe improvement in image quality.

---

# Results Summary

| Model | Accuracy |
|------|----------|
| Simple CNN | 88% |
| Transfer Learning | 92% |
| RNN | 82% |
| LSTM | 87% |
| GRU | 86% |

The GAN model successfully generated Fashion-MNIST images and image quality improved across epochs.

---

# Evaluation Metrics Used
The models were evaluated using:
- Accuracy
- Loss curves
- Confusion Matrix
- Generated Images
- Training Stability
- Model Comparison

---

# Conclusion
This project demonstrates the implementation of multiple deep learning models including CNN, Transfer Learning, RNN, LSTM, GRU, and GAN. The models were applied to different tasks including image classification, text classification, and image generation. Transfer learning achieved higher accuracy compared to the custom CNN model, while LSTM performed better than simple RNN. The GAN model successfully generated images and showed improvement across training epochs.
