# Sentiment Analysis of Amazon Reviews using SVM

This repository presents a sentiment analysis project focused on analyzing Amazon reviews using the Support Vector Machine (SVM) algorithm. The project aims to classify the sentiment of Amazon reviews into positive, negative, or neutral categories. Furthermore, the application is deployed using Streamlit, allowing users to interact with the sentiment analysis model through a user-friendly web interface.

## Dataset

The dataset utilized in this project consists of a collection of Amazon reviews across various product categories. Each review is associated with a rating and textual feedback provided by the reviewer. The dataset enables the exploration of sentiment patterns across different products and aids in understanding customer sentiments towards Amazon products.

## Project Structure

The project structure is organized as follows:

- **data:** Contains the dataset used for training and testing the sentiment analysis model.
- **notebooks:** Includes Jupyter notebooks detailing the data preprocessing steps, feature extraction, model development using SVM, and evaluation.
- **src:** Contains the Python code for deploying the sentiment analysis model using Streamlit.
- **requirements.txt:** Lists the necessary dependencies required to run the application.
- **README.md:** Provides instructions and information about the project.

## Data Preprocessing and Feature Extraction

Key aspects of data preprocessing and feature extraction include:

Text cleaning and normalization
Tokenization and vectorization
Removal of stopwords and punctuation
Stemming or lemmatization
Feature representation using TF-IDF or word embeddings

## Sentiment Analysis using SVM

The sentiment analysis task involves training an SVM classifier to classify reviews into positive, negative, or neutral sentiments. SVM is a powerful supervised learning algorithm known for its effectiveness in handling high-dimensional data and achieving good classification performance. Hyperparameter tuning may be performed to optimize the SVM model's performance.

## Streamlit Deployment

The sentiment analysis model is deployed using Streamlit, a Python library for building interactive web applications. The Streamlit application allows users to input Amazon reviews and receive real-time sentiment predictions. The deployed application provides an intuitive interface for users to interact with the sentiment analysis model without requiring any programming knowledge.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the directory.
3. Install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

4. Run the Streamlit application using the following command:

```bash
streamlit run app.py
```

5. Access the deployed application through the provided URL.

## Requirements

The project requires Python 3.11 along with various libraries such as pandas, joblib, scikit-learn, streamlit, etc. These dependencies are listed in the `requirements.txt` file.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.



Customize this README according to your project's specific details and preferences.
