# Sentiment Analysis Using SpaCy

This project demonstrates how to perform sentiment analysis using the `spaCy` library and a dataset of tweets. It preprocesses the text data and utilizes natural language processing (NLP) techniques to classify sentiment.

## Project Structure

- **Data Preprocessing**: Loads a CSV file containing tweet data and their corresponding sentiment labels.
- **NLP with SpaCy**: Uses `spaCy` to tokenize, process, and analyze the sentiment of the text data.

## Requirements

- Python 3.x
- pandas
- spacy

You can install the required dependencies by running:

```bash
pip install pandas spacy
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/sentiment-analysis-using-spacy.git
   ```

2. Navigate to the project directory:
   ```bash
   cd sentiment-analysis-using-spacy
   ```

3. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   Open the `sentiment-analysis-using-spacy.ipynb` file in Jupyter Notebook or JupyterLab and run the cells sequentially.

## Dataset

The dataset used is a CSV file with columns for tweet content and their respective sentiment labels (Positive, Negative, Neutral).

## Results

The notebook processes the dataset and utilizes `spaCy` to perform sentiment analysis. Results are displayed as predictions of tweet sentiments.
