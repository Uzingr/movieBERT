
# Bert Model for Predicting Tags Movies

In this Repo we use a Bert base Model in order to predict tags movies from a dataset called "mspt_full_data_csv".

## Directory Tree
- **data**: contains a custom dataset loading methods;
    - MovieDataset.py
    - filtered_mt.csv
    - mspt_full_data_csv
- **model**: contains a Bert Model for classifier and metrics for 10 epochs of the Model;
    - BERTClassifier.py
    - metrics_10epochs_2FCL.png
- **preprocessing**: contains a pyhton file for preprocessing of the Dataset;
    - Preprocessing.py
- **training**: contains the training and validation accuracy flow of our Bert Model;
    - Training.py
- **utils**: contains the methods to perform traing, validation and test; 
    - Utils.py
- Inference.py

# Description of the model
Our Bert model aims to predict film tags, given a carefully preprocessed dataset.
The dataset in question is a csv file containing film name, description and genre (maximum 3 types of genres). 
We preprocessed the dataset in order to define tokens to be passed to the model for learning.
We then used a basic Bert model (consisting of 12 Transformer Encoders) and defined suitable hyperparameters and started the training.
We evaluated various variants of the model (3 versions in particular) in order to improve its accuracy.


## Features of our Bert Model 

- Predicting tag movies from a given prompt
- Evaluation of model accuracy

## Authors

- [Giovanni Silvestri](https://www.github.com/vannisil)
- [Marcello Vangi](https://www.github.com/uzingr)
