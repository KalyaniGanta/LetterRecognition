# LetterRecognition

The NeuralNet.py file is attached to the submission, however upon opening the file, there is a link commented out at the top of the file to the google colab where the file was orginally created. I would recommend clicking this link and going to the google collab where all the information is organized. Once you have opened the link, begin by running the imports block of code at the top to import all the libraries used. After doing so, you can proceed to run the second block. Then finally run the last block of code which calls all the functions. Since it is running numerous neural networks it can take anywhere from 1-3 minutes. After running this block, you will recieve the accuracies for each of the train and test scores and the errors as well. The colors that are commented out on top of every neural network call in the second block correspond to the graphs which are included in the report. 

Libraries used:
# Required Libraries
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import sklearn

# Preprocessing
from sklearn.preprocessing import LabelEncoder
from sklearn.preprocessing import StandardScaler

# Neural Network
from sklearn.neural_network import MLPClassifier

# Data Manipulation and Evaluation
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.metrics import hinge_loss
