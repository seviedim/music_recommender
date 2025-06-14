# Music Recommender System

This project implements a music recommendation system designed to handle datasets without explicit user ratings. Traditional collaborative filtering methods often face challenges with sparse or incomplete rating data. To address this, the system uses **k-means clustering** to group users and items based on implicit interactions, improving recommendation accuracy.

## Features

- Handles sparse datasets lacking explicit ratings  
- Uses k-means clustering on implicit user-item interactions  
- Overcomes limitations of traditional collaborative filtering  
- Provides reliable music recommendations

## Technologies & Libraries Used

- Python  
- NumPy  
- Pandas  
- SciPy (for sparse matrix operations and SVD)  
- Matplotlib & Seaborn (for visualization)

## Usage

1. Clone the repository  
2. Install the required libraries:  
   ```bash
   pip install numpy pandas scipy matplotlib seaborn
