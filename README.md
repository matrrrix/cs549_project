# K-Emotion Sentiment Analysis for CS 549 at San Diego State University

A project by Riley Mathews, Elias Mapendo, and Logan Wolff.

Sentiment analysis describes the act of computationally identifying a writer’s attitude toward a specific topic.

Cases include:
    - Movie reviews
    - Customer feedback
    - Public reactions

Our group noticed how sentiment analysis is usually implying either a positive and negative tone, and wanted to train a model extending the scope to K Emotions.

## Dataset

Hugging Face is an open-source machine learning platform that, among other tools, provides access to datasets and models.

The Hugging Face dataset from user dalopeza98 titled isear-cleaned-dataset provided organized text and labels relating to the ISEAR project.
https://huggingface.co/datasets/dalopeza98/isear-cleaned-dataset

The ISEAR project was an effort from psychologists around the globe in the 1990s to survey student respondents on situations in which they had experienced 7 major emotions.


## Model

Google introduced a language model titled BERT in the October of 2018.
BERT stands for Bidirectional Encoder Representations from Transformers
Transformer Architecture High level overview:
    - Text is broken into tokens
    - Tokens are converted into embedded vectors
    - Embedded vectors are then utilized to predict next likely tokens

google-bert/bert-base-uncased on Hugging Face
https://huggingface.co/google-bert/bert-base-uncased

Our course of action was to fine-tune the BERT model with respect to the ISEAR dataset containing 7 classes. 

## Running the python notebook file

To run the notebook file, Google Colaboratory is recommended. The RAM required for training is past the capabilities of the average laptop or PC.
