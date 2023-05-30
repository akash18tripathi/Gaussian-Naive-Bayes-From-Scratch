# Gaussian-Naive-Bayes-From-Scratch

This repository contains the implementation of Gaussian Naive Bayes in a Jupyter Notebook. Gaussian Naive Bayes is a simple and effective algorithm for classification tasks. It is based on Bayes' theorem with the assumption of independence between the features.

## Concepts

### Bayes' Theorem

Bayes' theorem is a fundamental concept in probability theory and statistics. It provides a way to calculate the probability of an event based on prior knowledge or information. The formula for Bayes' theorem is as follows:

P(A|B) = (P(B|A) * P(A)) / P(B)

where:
- P(A|B) is the probability of event A occurring given that event B has occurred.
- P(B|A) is the probability of event B occurring given that event A has occurred.
- P(A) is the prior probability of event A.
- P(B) is the prior probability of event B.

### Gaussian Naive Bayes

Gaussian Naive Bayes is a variant of Naive Bayes that assumes the likelihood of the features follows a Gaussian distribution (i.e., normal distribution). It is called "naive" because it assumes independence between the features, meaning that the presence or absence of one feature does not affect the presence or absence of another feature.

The formula for Gaussian Naive Bayes can be expressed as:

P(y|X) = (1 / Z) * P(y) * Π P(xi|y)

where:
- P(y|X) is the posterior probability of class y given the features X.
- Z is a normalization constant.
- P(y) is the prior probability of class y.
- Π P(xi|y) is the product of the likelihoods of each feature xi given class y.

## Jupyter Notebook

The Jupyter Notebook in this repository contains the implementation of Gaussian Naive Bayes using Python. It includes the necessary code and explanations to understand the algorithm and apply it to classification tasks.

## Dataset

The dataset used in this project is the Wireless Indoor Localization Data Set, which provides information about the signal strengths of seven Wi-Fi routers in an office environment. The dataset helps to classify the location of the receiver into one of four rooms based on these signal strengths. 

You can find dataset [here](https://archive.ics.uci.edu/ml/datasets/Wireless+Indoor+Localization)

### Dataset Details

- Number of samples: 2000
- Number of attributes: 7
- Class label: 4 values representing the room categories

### File Location

The dataset file `wifiLocalization.txt` contains the data used in this project. It is present in the root directory of this repository.

## Contributing

Contributions are welcome and encouraged!
