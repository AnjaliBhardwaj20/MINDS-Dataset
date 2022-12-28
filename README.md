# MINDS-Dataset
**MINDS** (**M**ulti-label emot**I**o**N** and sentiment classification **D**ata**S**et) is a large-scale multi-labeled dataset, containing 227,229 instances.
The tweets were collected using the top-six trending hashtags – *#Omicron*, *#OmicronVariant*, *#OmicronVarient*, *#OmicronInIndia*, *#OmicronVirus*, and *#Omicronvirus india* from December 17, 2021 to February 4, 2022 using Twitter’s Tweepy API.
Each instance in the dataset is classified according to three sentiment classes are: positive, negative, and neutral and five emotion classes are: *sadness*, *joy*, *fear*, *disgust*, and *anger*. 
Using a multi-model setup, namely *IBM Watson NLU API*, *Komprehend Text Analysis API*, and *Text2emotion python package* to annotate the dataset to quantify all aspects of model uncertainty.

For more details on the design and content of the dataset, please see our paper.

## Dataset
This directory includes the dataset is in CSV format for aformentioned hashtags. 

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
