# Product Classification for Procurement

Assign free-text product descriptions from a digital procurement platform to the right UNSPSC category automatically, at a scale where manual tagging is not practical.

## Approach

- Text matching with TF-IDF and CountVectorizer, including a noun-only variant
- Semantic matching with Sentence Transformers and cosine similarity against UNSPSC categories
- Named entity recognition with spaCy and Hugging Face to extract product names, dimensions and brands
- Comparison of combined TF-IDF and Sentence Transformer approaches

## Start here

[src/TFIDF_SentenceTransformers.ipynb](src/TFIDF_SentenceTransformers.ipynb)

## Data

The source data and notebook outputs are not included in this repository, so the notebooks show the code and method only.
