# Github Readme file for Colab Code
## Introduction
This code demonstrates an implementation of the BM25+RD (BM25 with relevance feedback) algorithm for information retrieval. The algorithm calculates scores for documents in a corpus based on the relevance of a user query. The code uses a preprocessed corpus of text documents, and the relevance feedback is based on the user's feedback to the retrieved results.

## Information Retrieval using BM25+RD
This project is about building an information retrieval system using the BM25+RD scoring function. The system collects a corpus of text documents, preprocesses them, calculates term frequencies, and builds an inverted index.

## Requirements
The following packages are required to run this code:

nltk
PyPDF2
To install them, run the following command:

!pip install nltk PyPDF2

## Usage
Clone the repository:

git clone https://github.com/your_username/information-retrieval-bm25rd.git

Navigate to the project directory:
cd information-retrieval-bm25rd

Run the bm25rd.py file with the input directory containing the text documents as an argument:
python bm25rd.py input_dir/
Enter your query when prompted.

## References
T. Y. Liu, Learning to Rank for Information Retrieval
