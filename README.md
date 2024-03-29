# Naive Bayes Spam Classifier

This repository contains code for training a Naive Bayes spam classifier using scikit-learn.

## Code Overview

- [`spam_classifier.ipynb`](spam_classifier.ipynb): Jupyter Notebook containing the code for the spam classifier.
- [`spam.csv`](spam.csv): Dataset used for training and testing.

## Instructions

1. Clone this repository to your local machine.
2. Install the required libraries by running: `pip install pandas numpy scikit-learn`.
3. Run the Jupyter Notebook `spam_classifier.ipynb` to see the step-by-step process of building the spam classifier.

## Usage

1. Open the Jupyter Notebook `spam_classifier.ipynb`.
2. Follow along with the code to preprocess the data, build the model, and evaluate its performance.
3. Modify the `emails` list to test the model with new emails.
4. The code uses the Bag of Words vectorizer to convert text data into numerical features.
5. The classification algorithm used in this project is Naive Bayes.

## Naive Bayes Classifier

The Naive Bayes algorithm is a probabilistic classification technique based on Bayes' theorem. It's particularly effective for text classification tasks, such as spam detection and sentiment analysis. Despite its simple assumption of feature independence, Naive Bayes often works well for many real-world text datasets.

## Results

The trained Naive Bayes model achieved an accuracy of approximately 99% on the test data.

## Bag of Words Vectorizer

The Bag of Words vectorizer is used to convert text data into a numerical representation that can be used by machine learning algorithms. It creates a sparse matrix where each row represents a document (or email in this case) and each column represents a unique word in the dataset. The value in each cell represents the frequency of that word in the corresponding document.


## Contact

For any questions or inquiries, feel free to contact [saatviksrivastaav25@gmail.com] or (https://github.com/saatvik25).
