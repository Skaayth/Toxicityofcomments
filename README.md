# Toxicity of comments

## About
Using Natural language processing and deep learning this model can recognise comments that are toxic, threatening or insulting. Can be useful for platforms like Wikipedia and YouTube to check the toxicity of comments.

![20128](https://github.com/Skaayth/Toxicityofcomments/blob/main/AEEA8DBE-B8F9-4EA1-8594-A0DABB4341C9_4_5005_c.jpeg)


## Aim
The aim is to create a model which predicts a probability of each type of toxicity for each comment.
We use embedding layer and LSTMs to train the model.

## Notebook
The .ipynb file contains all the code from importing the required libraries -> Importing Data -> Data Preprocessing -> Training the Model.


## Dataset

The dataset has been taken from [HERE](https://www.kaggle.com/datasets/julian3833/jigsaw-toxic-comment-classification-challenge)

This is a dataset of comments from Wikipedia’s talk page edits
The types of toxicity are:
**{'toxic'
'severe_toxic'
'obscene'
'threat'
'insult'
'identity_hate'}**


