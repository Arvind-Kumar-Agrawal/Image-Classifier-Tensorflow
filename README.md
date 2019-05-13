# TensorFlow Multiclass Image Classification using CNNs
This is a multiclass image classification project using Convolutional Neural Networks and TensorFlow API on Python.

It is a ready-to-run code.


# Dependencies

```pip3 install -r requirements.txt```

# Training
Training on GPU:

```python3 multiclass_classification_gpu.py ```

Training on CPU:

```python3 multiclass_classification_cpu.py ```

# Notebook

```jupyter lab  Multiclass_classification.ipynb``` or ```jupyter notebook Multiclass_classification.ipynb ```

# Data


This is a repository containing datasets of 5200 training images of 4 classes and 1267 testing images.No problematic image.

it can be downloaded from https://drive.google.com/file/d/1jAiGXRfNGJfCjfwSix70sVFfq9r8mxPd/view?usp=sharing

train_data_bi.npy is containing 5200 training photos with labels.

test_data_bi.npy is containing 1267 testing photos with labels.

Classes are chair & kitchen & knife & saucepan. Classes are equal(1300 glass - 1300 kitchen - 1300 knife- 1300 saucepan) on training data. 



# Architecture

AlexNet is used as architecture. 5 convolution layers and 3 Fully Connected Layers with 0.5 Dropout Ratio. 60 million Parameters.


# Results
Accuracy score reached 87% on CV after just 5 epochs.


# Predictions
Predictions for first 64 testing images are below. Titles are  the predictions of our Model.
