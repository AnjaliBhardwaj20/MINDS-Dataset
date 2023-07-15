# MINDS-Dataset
**MINDS** (**M**ulti-label emot**I**o**N** and sentiment classification **D**ata**S**et) is a large-scale multi-labeled dataset containing 227,229 instances.
The tweets were collected using the top-six trending hashtags – *#Omicron*, *#OmicronVariant*, *#OmicronVarient*, *#OmicronInIndia*, *#OmicronVirus*, and *#Omicronvirus india* from December 17, 2021 to February 4, 2022 using Twitter’s Tweepy API.
Each instance in the dataset is classified according to three sentiment classes: positive, negative, and neutral and the five emotion classes: *sadness*, *joy*, *fear*, *disgust*, and *anger*. 
Using a multi-model setup, namely *IBM Watson NLU API*, *Komprehend Text Analysis API*, and *Text2emotion python package* to annotate the dataset to quantify all aspects of model uncertainty.
Due to the Twitter policy, ids, text, and their respective labels (Sentiment_Score, Sentiment_Label, Emotion_Sadness, Emotion_Joy, Emotion_Fear, Emotion_Disgust, and Emotion_Anger) are shared for the MINDS dataset.

This directory includes the dataset in CSV format for the aformentioned hashtags.

For more details on the design and content of the dataset, please see our [paper](https://ceur-ws.org/Vol-3416/paper_2.pdf).

-------------------------
Pre-requisite:
-------------------------
1. Twitter Tweepy-4.6.0 API
2. Python 3.6
3. Numpy
4. Pandas
5. IBM Watson NLU API
6. Komprehend Text Analysis API
7. Text2emotion python package

## Cite paper:
Bhardwaj, A., & Abulaish, M. (2023). MINDS: A Multi-label Emotion and Sentiment Classification Dataset Related to COVID-19, In Proceedings of the WNLPe-Health 2022: The First Workshop on Context-aware NLP in eHealth, Co-located with the 19th International Conference on Natural Language Processing (ICON), IIIT Delhi, India, December 15-18, 2022.
