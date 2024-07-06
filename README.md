# NLP Sentiment Analysis Project

## Overview

This project demonstrates a simple Natural Language Processing (NLP) application for sentiment analysis on movie reviews. It uses the NLTK library's movie reviews dataset and the TextBlob library for sentiment classification.

## Features

1. Sentiment analysis on pre-existing movie reviews dataset
2. Interactive sentiment analysis for user-input movie reviews
3. Simple command-line interface for easy interaction

## Requirements

- Python 3.x
- NLTK
- TextBlob

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/nlp-sentiment-analysis.git
   cd nlp-sentiment-analysis
   ```

2. Install the required libraries:
   ```
   pip install nltk textblob
   ```

3. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('movie_reviews')
   nltk.download('punkt')
   ```

## Usage

1. Run the Jupyter notebook:
   ```
   jupyter notebook NLP_Presentation.ipynb
   ```

2. Execute the cells in order to:
   - Install and import necessary libraries
   - Load and prepare the movie reviews dataset
   - Test the sentiment analysis on sample reviews
   - Run the interactive sentiment analysis function

3. For the interactive sentiment analysis:
   - Enter a movie review when prompted
   - The program will classify the sentiment as Positive or Negative
   - Type 'exit' to quit the interactive session

## How It Works

1. The project uses the NLTK movie reviews dataset, which contains labeled positive and negative reviews.
2. The TextBlob library is used to perform sentiment analysis on the text.
3. A simple classification function determines if a review is positive or negative based on its polarity score.
4. The interactive function allows users to input their own reviews for real-time sentiment analysis.

## Limitations and Future Improvements

- The current model uses a simple polarity threshold for classification, which may not capture nuanced sentiments.
- Future versions could implement more advanced NLP techniques such as:
  - Custom training on the movie reviews dataset
  - Use of more advanced models like BERT or RoBERTa
  - Incorporation of aspect-based sentiment analysis

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- NLTK for providing the movie reviews dataset
- TextBlob developers for their simple yet effective NLP library