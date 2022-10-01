# NLP-coursework
Coursework material for introduction to NLP

# Syllabus

## Objectives

This course aims to provide concrete toolkit for data scientists or software engineers willing to perform natural language processing tasks.
At the end of the course, the students should be able to develop a full NLP pipeline:
* Preprocess and analyze raw text data
* Represent text data into vectors and manipulate them
* Train a supervised model in order to achieve standard NLP tasks (e.g. classification, Named Entity Recognition)
* Serve the model for inference on new data

In addition, the students will learn to leverage pre-trained models (e.g. Word2Vec, BERT).

This course aims to be practical. Therefore we will manipulate real-word raw datasets from open source projects such as DataGouv.
Also, students will package their Python code into a library and share their code to a Github repository.

## Prerequisites
* Python: some knowledge of the main ML libraries: Pandas, Numpy, Sklearn
* Basic linear algebra and statistics skills

## Tools
* Environment: Jupyter Notebook, Google collab, Github
* Python libraries: Keras / Tensforflow, SpacY, sklearn, ...

## Organisation

During each session, students will start from a Jupyter Notebook template and will produce their own code. Each template gives some guidelines and toy examples relevant to the topic of the session. Additional resources will be shared between sessions in order to introduce the theoritical concepts.

## Content - Part A

### Data
We will work on the dataset of [avis et conseils de la CADA](https://www.data.gouv.fr/fr/datasets/avis-et-conseils-de-la-cada/) from [datagouv.fr](http://datagouv.fr). This dataset contains documents from French public authorities. Each document is related to an opinion, which belongs to either favorable, unfavorable or neutral categories.

### Objective
This is a supervised classification task. The objective is to classify these documents into one of the above categories.

### Data exploration
Analyze the shape of documents, distribution of words, topic modelling, etc...

### Preprocessing
Build a preprocessing pipeline:
* Tokenization
* Text normalisation (eg lemmatisation)
* Representation into vectors

### Modelling
#### Baseline model
Let's build a first baseline model with a simple ML classifier.
Test the results on a holdout sample.

#### Deep Learning
Build a deep learning classifier with various configurations.

#### Pre-trained embeddings
Can we perform better by leveraging well defined linguistic properties of a pre-trained model ?

## Content - Part B

In the next part we will perform a Named Entity Recognition task.

__To be completed__

## Bibliography
TBD
