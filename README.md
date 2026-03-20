# BookWise – Content-Based Book Recommender

**Author:** Hadi Akbar

## Overview

**BookWise** is a content-based book recommendation system that leverages sentence embeddings to understand the semantic meaning of book descriptions. It demonstrates how raw text can be transformed into dense vectors and used to identify similar books. The system supports recommendations based on a single book or a user’s entire reading history.

## Features

- Embed book descriptions using **MiniLM** and **Nomic** models  
- Compute **cosine similarity** to find the most similar books  
- Generate recommendations for a **single book** or multiple books in a user's reading history  
- Filter recommendations by **genre**  
- Embed and query **new, user-provided books**  
- Includes exploratory data analysis of the dataset  

## Technologies

- **Python**  
- **Pandas** for data manipulation  
- **NumPy** for numerical operations  
- **Scikit-learn** for cosine similarity computations  
- **Sentence-Transformers** for generating sentence embeddings  

## Dataset

The project uses a small, hand-crafted dataset of 12 books, each with a title, genre, and description. The system can be extended by adding more books or importing descriptions from other sources.

## Usage

1. Load the dataset and pre-trained models  
2. Compute embeddings for book descriptions  
3. Use the recommendation functions to find similar books  
4. Optionally, filter recommendations by genre or embed new books  
5. Extend the system by adding user preferences to generate personalized recommendations  

## Objective

This project provides practical experience with **text embeddings, semantic similarity, and content-based recommendation systems**, and demonstrates how NLP models can be repurposed for recommendation tasks.
