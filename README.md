
# NLP Sentiment Analysis Project

This repository contains two Jupyter notebooks that showcase sentiment analysis using Natural Language Processing (NLP) techniques. The project demonstrates two different approaches: one using a simple model and another using a more advanced, cutting-edge model based on BERT.

## Files

1. **`NLP_Presentation.ipynb`**
   - **Description**: This notebook contains a simple implementation of sentiment analysis. It showcases basic NLP techniques to classify text as positive, negative, or neutral.
   - **Usage**: Suitable for educational purposes and simple text classification tasks.
   - **Key Libraries Used**:
     - `sklearn`
     - `nltk`
     - `pandas`

2. **`Sentiment_Analysis_with_BERT.ipynb`**
   - **Description**: This notebook provides an advanced sentiment analysis using a pre-trained BERT model. It handles more complex text inputs, offering detailed sentiment classification with sentiment strength and confidence levels.
   - **Usage**: Ideal for projects requiring cutting-edge sentiment analysis with nuanced understanding of text.
   - **Key Libraries Used**:
     - `transformers`
     - `torch`
     - `datasets`

## Installation

To run the notebooks, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Eisen9/NLP-Sentiment-Analysis-Project.git
   cd NLP-Sentiment-Analysis-Project
   

2. **Install the necessary dependencies**:
   - For the simple notebook, install the following libraries:
     ```bash
     pip install nltk pandas scikit-learn
     ```
   - For the BERT-based advanced notebook, install these:
     ```bash
     pip install transformers torch datasets
     ```

3. **Run the notebooks**:
   - Open either notebook in Jupyter or Google Colab to begin testing sentiment analysis:
     - `NLP_Presentation.ipynb`: Basic Sentiment Analysis
     - `Sentiment_Analysis_with_BERT.ipynb`: Advanced Sentiment Analysis with BERT

## Contributing

Feel free to fork this repository, submit pull requests, or suggest features and improvements.
```