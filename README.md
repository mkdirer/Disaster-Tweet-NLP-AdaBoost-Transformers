# Disaster-Tweet-NLP-AdaBoost-Transformers

This project aims to recognize whether a given tweet is about a disaster or not. The task is solved using transformers with the AdaBoost technique. 

## Project Stages

1. Data Loading and Preprocessing
2. Analyzing and displaying the most popular tweet locations on an interactive map
3. Analyzing the class distribution in the training set
4. Data processing - removing punctuation, special characters, and emojis
5. Utilizing an external file for word vectorization
6. Tokenizing tweets and creating word vectors
7. Splitting data into training and validation sets
8. Implementing the AdaBoost mechanism
9. Implementing a transformer-based classifier
10. Training the classifier and evaluating the results

## Achieved Results

After training the classifier, we achieved an accuracy of approximately 80% on the validation set.

## Requirements

To run this project, you need the following libraries and tools:
- pandas
- matplotlib
- numpy
- re
- geopy
- folium
- nltk
- keras
- tensorflow
- sklearn
- livelossplot

The training and test datasets are provided in the files `train.csv` and `test.csv`. Additionally, you need to download the file `glove.twitter.27B.200d.txt` and place it in the project directory.

## How to Run

To run this project, follow these steps:
1. Install the required libraries if you haven't already.
2. Download the training and test datasets from the appropriate sources and place them in the files `train.csv` and `test.csv`.
3. Run the Jupyter Notebook file `switch_transformers.ipynb`.
