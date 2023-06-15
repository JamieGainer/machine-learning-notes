# Case Study/ Quick Kaggle Project for NLP

## Types of NLP Project

1. Classification
2. Text prediction/ generation
3. Sentiment analysis
4. Question answering
5. Automatic summarization
6. Part of speech
7. Generate word embeddings
8. Optical character recognition
9. Speech to text
10. Translation

References:
https://jamesmccaffrey.wordpress.com/2020/07/17/ten-types-of-neural-based-natural-language-processing-nlp-problems/
https://analyticsindiamag.com/8-different-nlp-scenarios-one-can-take-up-for-a-project/

## Example 1: Disaster Tweets

This example follows the Kaggle "Getting Started with NLP" competition.
The data is labeled tweets which either do or do not describe a disaster.

I am not including the datasets (or any Kaggle datasets) in this repo.
To get the data to run the notebook
1. Make a new directory: machine-learning-notes/Case_Study_Notes/nlp-getting-started
2. Download a zip file with datasets for the competition using the
kaggle competitions download -c nlp-getting-started
command
3. Unzip the zip file.  There should now be a train.csv and test.csv file in the machine-learning-notes/Case_Study_Notes/nlp-getting-started directory

If running the "kaggle competitions download" command doesn't work, install kaggle following the instructions
(here)[https://github.com/Kaggle/kaggle-api#readme] 

### CountVectorizer

sklearn.feature_extraction.text.CountVectorizer

Can obtain "bag of word" vectors for each sentence/ tweet/ review/ whatever...

### TF-IDF



### Embedding Vectors


