# Email & SMS Spam Classifier

## Overview

The **Email & SMS Spam Classifier** is a machine learning-based project designed to classify whether a given email or SMS message is **spam** or **ham (non-spam)**. The classifier leverages natural language processing (NLP) techniques and machine learning algorithms to analyze textual data and categorize messages accurately.

In today’s world, spam messages can clog our email inboxes and SMS systems, making it essential to develop reliable filters to automatically detect and block such messages. This project builds a classifier to automate this process, helping to prevent unwanted messages from reaching the user.

## Key Features

- **Spam vs. Ham Classification**: Classifies messages into spam and non-spam categories.
- **Data Preprocessing**: The project performs various preprocessing steps to clean and prepare the data for training.
- **Multiple Models**: The project uses multiple machine learning models to train the classifier, including Naive Bayes, Logistic Regression, and more.
- **Performance Evaluation**: Evaluation of the model's performance based on key metrics like accuracy, precision, recall, and F1-score.

## Dataset

The dataset used in this project is a collection of labeled emails and SMS messages. Each message is classified into one of two categories:
- **Spam**: Unwanted, unsolicited, or junk messages.
- **Ham**: Non-spam, legitimate messages.

### Dataset Features:
- **Text**: The content of the email/SMS message.
- **Label**: The classification of the message (either **spam** or **ham**).

## Installation

To get started with the project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/BrijeshRakhasiya/Email---SMS-Spam-Classifier.git
cd Email---SMS-Spam-Classifier
pip install -r requirements.txt
```
