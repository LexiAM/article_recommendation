# Article Recommendation Engine

## Summary
In this project, we build a recommendation engine for recommending articles on IBM Watson Studio platform. We build functions to provide rank, content, and collaborative filtering recommendations. Content filetring is accomplished using article cosine similarity based on descriptions and titles using NLP with `spacy` and TFIDF vectorization. 

## Project Structure
```
|-- Recommendation_with_IBM.ipynb - notebook containing recommendation engine development code
|-- Recommendation_with_IBM.ipynb  - html version of the notebook
|-- project_tests.py - tests for various functions and code blocks
|-- top_5.p - test cases
|-- top_10.p - test cases
|-- top_20.p - test cases
|-- user_item_matrix.p - pickle file of the user-item-matrix
```

## Requirements
Python 3.6 with the following packages:
```
pandas
numpy
matplotlib
pickle
spacy
sklearn
```

## Acknowledgements
Udacity for providing template and test cases