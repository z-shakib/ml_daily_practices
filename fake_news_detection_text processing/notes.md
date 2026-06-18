# Fake News Detection using basic NLP preprocessing and TF-IDF.

## Dataset

The dataset contains news article information such as title, author, text, and label.

Label meaning:

* 0 = Real News
* 1 = Fake News

## What I Learned

Machine Learning models cannot directly understand raw text, so text data needs to be cleaned and converted into numbers.

## Main Steps

1. Loaded the fake news dataset
2. Checked and handled missing values
3. Combined author and title into one text column
4. Cleaned the text by removing unnecessary symbols and numbers
5. Converted all words to lowercase
6. Removed common stopwords like “the”, “is”, “are”
7. Applied stemming to reduce words to root form
8. Used TF-IDF to convert text into numerical feature vectors

## Key Concepts

Stopwords are common words that do not add much meaning.

Stemming reduces words to their root form.

Example:
running, runs, runner → run

TF-IDF gives importance scores to words. Common words get lower value, and important words get higher value.

## Summary

Today I practiced text preprocessing for fake news detection. I learned how to clean raw text and convert it into numerical form using TF-IDF so that it becomes ready for Machine Learning model training.
