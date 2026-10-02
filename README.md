# Mental Health Detection from Social Media Text

A text classification project using NLP and Transformer models to classify social media statements into different mental health-related categories.

## Dataset

The dataset contains social media statements with the following categories:

- Anxiety
- Bipolar
- Depression
- Normal
- Personality disorder
- Stress
- Suicidal

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NLP
- TF-IDF
- Logistic Regression
- Hugging Face Transformers
- DistilBERT
- PyTorch

## Models

### 1. TF-IDF + Logistic Regression

Accuracy: **76.58%**

### 2. DistilBERT

For practice, a small sample of 300 records was used for Transformer training.

Accuracy: **56.67%**

## Example Prediction

Input:

> I feel very sad, hopeless and tired all the time.

Predicted category:

**Depression**

## Conclusion

The project demonstrates how traditional NLP techniques and Transformer-based models can be used for text classification.

The DistilBERT result was based on a very small training sample and one training epoch, so it should not be considered a full comparison of the two approaches.

**Note:** This project is for educational and text-classification purposes only. It is not a medical diagnostic system.