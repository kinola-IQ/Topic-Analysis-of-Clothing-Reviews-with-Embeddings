# Women's Clothing E-Commerce Reviews Project

Welcome to the Women's Clothing E-Commerce Reviews project! This repository explores customer feedback from an e-commerce platform, focusing on the "Review Text" column to uncover valuable insights about shopping experiences and product quality.

## Project Overview

This project leverages text embeddings and Python to analyze customer reviews, identify underlying themes, and understand customer sentiments. The goal is to help improve customer service and product offerings by extracting actionable insights from real customer feedback.

## Dataset

- **File:** `womens_clothing_e-commerce_reviews.csv`
- **Relevant Column:** `Review Text` — Textual feedback provided by customers about their shopping experience and product quality.

## Key Steps

1. **Data Loading:** Import and inspect the dataset to ensure relevant data is used.
2. **Embeddings Creation:** Use embedding API services and ChromaDB to process and store review embeddings.
3. **Dimensionality Reduction:** Apply t-SNE for visualizing high-dimensional embeddings in 2D.
4. **Visualization:** Plot embeddings colored by review ratings to identify patterns.
5. **Feedback Categorization:** Search for themes like quality, fit, style, and comfort within reviews.
6. **Similarity Search:** Find reviews similar to a given comment using embedding-based queries.

## Requirements

- Python 3.8+
- pandas
- scikit-learn
- matplotlib
- chromadb==0.4.17
- pysqlite3-binary==0.5.2

## Getting Started

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt