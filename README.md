
# Movie Recommendation System

**Author:** Pavithra Selvan  
**Course:** ITIS 6162 - Data Mining  
**Assignment:** Programming Assignment – Recommendation Algorithms  
**Repository Name:** datamining_recommendersystem
---

## Overview

This project implements a movie recommendation system using multiple approaches:

1.  Exploratory Data Analysis (EDA)
2.  Collaborative Filtering (User- and Item-Based)
3.  Graph-Based Recommendations (Pixie-Inspired Random Walks)

---

## Project Structure

### Part 1: Exploratory Data Analysis
- Analyzes user behavior, rating distributions, and movie popularity.
- Visual insights guide modeling decisions for recommendation strategies.

### Part 2: Collaborative Filtering
- **User-Based Filtering**: Finds similar users based on rating profiles.
- **Item-Based Filtering**: Recommends movies similar to those a user liked.
- **Cosine Similarity** is used for computing similarity scores.

### Part 3: Graph-Based Recommendations (Pixie)
- Constructs a **user–movie bipartite graph**.
- Implements **random walks** to recommend:
  - Movies for users
  - Similar movies for a given movie
- Two versions:
  - **Unweighted Pixie**: Simple walk without bias.
  - **Weighted Pixie**: Biases walk using edge weights (e.g., rating strength).

---

##  Technologies Used
Language: Python

| Tool/Library       | Purpose                        |
|--------------------|--------------------------------|
| `pandas`           | Data manipulation              |
| `numpy`            | Numerical operations           |
| `scikit-learn`     | Cosine similarity              |
| `random`           | Random walk selection          |

---

## Output & Interpretation

- Top-5 movie recommendations are generated for a user or a movie.
- Weighted walks better reflect user preference strength.
- Pixie-based methods simulate discovery-driven recommendations (similar to Pinterest’s approach).

---

## Files

- `DataMining_Programming_Assignment_pavithra.ipynb` — Main Jupyter notebook
- `README.md` — You’re here
- `Data/` — Raw data and preprocessed csv files

---

## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/PavithraSelvan169/datamining_recommendersystem.git
  
