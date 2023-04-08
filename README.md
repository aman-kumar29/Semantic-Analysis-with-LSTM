# Semantic-Analysis-with-LSTM
This repository contains code for training and using an LSTM-based model for sentiment analysis on a large dataset of Amazon product reviews.The model uses word embeddings and spatial dropout to handle variable-length input sequences, and is trained using a categorical cross-entropy loss and the Adam optimizer.

The code includes data preprocessing, model training, and prediction on new text data. The model is saved both as a Keras HDF5 file and as a JSON file with a weight manifest, allowing for easy reuse and modification.

The repository also includes a Jupyter notebook demonstrating the data analysis and model development process, as well as the resulting performance on a held-out test set.
# Dataset Used
You can find the dataset used [here](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews) 

# Dependencies
##### 1. Python 3.6 or later
##### 2. TensorFlow 2.x
##### 3. Keras
##### 4. NumPy
##### 5. Pandas
##### 6. NLTK
##### 7. Matplotlib

