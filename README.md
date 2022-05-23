# CSE676-music-genre-classification


This project is designed to use a short-time Fourier transformation of the data to classify the genres of the music instead of directly training with the audio itself. The transformed data is then trained with a CNN model, FNN model, and an SVM machine. Several metrics evaluate the model’s performance, and we use the SVM machine to compare and measure the effectiveness and accuracy of the deep learning model. The models described in this project can be used to classify the genres of the music using a method that is different from the original way of training the audio data itself and can be used to develop further models to help look for the clear difference between different genres of music. 


## Data
Data is collected from https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification, Kaggle. However, since the file under the root ./Data/genres_original/jazz/jazz.00054.wav is a broken file, please replace it with the jazz.00054.wav file provided in the masterbanch of the repo.

After download the dataset from the above link, please make sure the file KNN_FNN.ipynd is placed in the same folder level with the file features_30_sec.csv

## Code
The code is in the form of ipynd and is written via the Jupyter Notebook. It should also regenerate our model and result by running the files in a Jupyter Notebook. Before running the preprocessing part of each model, please modify the general_path value to the path of the Data folder of the dataset. The version of the librosa library we used are 0.9.1. It might cause failure if the version of the package is wrong. 
