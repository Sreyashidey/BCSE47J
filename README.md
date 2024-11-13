# Amazon Reviews Sentiment Analysis with BERT

This project demonstrates a sentiment analysis on Amazon reviews using the BERT model. It uses `bert-tensorflow` for text processing and TensorFlow Hub to fine-tune BERT embeddings for classification tasks. This notebook is designed to evaluate how well BERT can classify reviews as positive or negative based on the provided Amazon dataset.

## Project Structure

- **Data Preprocessing**: Includes text cleaning and tokenization using BERT's `FullTokenizer`.
- **Model Building**: Constructs a BERT-based classification model using `tensorflow_hub`.
- **Training and Evaluation**: Splits the dataset, trains the model, and evaluates its performance on the test set.
- **Visualization**: Provides insights into model performance through visualizations.

## Setup

To run this notebook, install the required packages:

```bash
pip install bert-tensorflow tqdm tensorflow_hub
```
##  Usage
- Clone this repository and navigate to the project directory.
- Run the notebook using Jupyter or Google Colab

## Results
This project aims to analyze the effectiveness of BERT in sentiment classification on real-world data from Amazon reviews.
