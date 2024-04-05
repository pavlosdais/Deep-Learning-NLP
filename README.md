# General Elections Classifier

Deep learning models for sentiment analysis classification of greek general election tweets into 3 categories:
- Positive
- Neutral
- Negative

Four different classifiers have been developed on the same datasets using real twitter data:

## [Softmax Regression](https://github.com/pavlosdais/NLP/blob/main/SoftmaxRegression)
In short, experimented with:

- Data preprocessing
- Different vectorizers (count, BoW, TF-IDF)
- Removal of features with very low/high frequency by adding max-df / min-df parameters
- Hyperparameter optimization using the Optuna framework

Place `36/114` at the course's [kaggle](https://www.kaggle.com/competitions/ys19-2023-assignment-1/leaderboard) competition.

## [Feed Forward Neural Network](https://github.com/pavlosdais/NLP/blob/main/FFNN)
In short, experimented with:

- Data preprocessing
- Different number of layers, neurons per layer & learning rates
- Activation functions (Linear & non-linear)
- Dropout layers
- Different optimizers (Stochastic Gradient Descent, Adam)
- Early stopping
- Hyperparameter optimization using the Optuna framework


Place `1/95` at the course's [kaggle](https://www.kaggle.com/competitions/ys19-2023-assignment-2/leaderboard) competition.

## [Recurrent Neural Network](https://github.com/pavlosdais/NLP/blob/main/RNN)
In short, experimented with:

- Data preprocessing
- Bidirectional stacked RNN's with LSTM/GRU cells
- Gradient Clipping
- Early stopping
- Skip connections
- Attention to the best model
- Hyperparameter optimization using the Optuna framework

Place `1/84` at the course's [kaggle](https://www.kaggle.com/competitions/ys19-2023-assignment-3/leaderboard) competition.

## [BERT](https://github.com/pavlosdais/NLP/blob/main/BERT)
In short, experimented with:

- Data preprocessing
- BertModel
- DistilBertModel
- Adding dropout layers
- Hyperparameter optimization using the Optuna framework

Place `6/70` at the course's [kaggle](https://www.kaggle.com/competitions/ys19-2023-assignment-4a/leaderboard) competition.

## About
The models were created for the [Artificial Intelligence II](https://www.di.uoa.gr/en/studies/undergraduate/805) course under prof. [Manolis Koubarakis](https://cgi.di.uoa.gr/~koubarak/).
