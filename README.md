Image Classification Challenge

This project was completed as part of a challenge aiming to perform image classification using TensorFlow and Keras.

Dataset

The dataset used for this project was downloaded from Kaggle, specifically the NEU Surface Defect Database. The dataset is divided into train and test sets, and it was utilized for training and evaluating the image classification model.

Task - Image Classification

For the classification task, TensorFlow (Version: 2.15) with the high-level API Keras was used to create a model for image classification. A pre-trained Xception DNN model, fine-tuned on the dataset, was utilized. The model architecture included BatchNormalization, GlobalAveragePooling2D, Dense layers with relu activation, dropout, and a final Dense layer with softmax activation for classification. The model was compiled with SparseCategoricalCrossentropy loss function and trained and tested on the train/test datasets.

Results

Validation Accuracy: 0.7666666507720947
