# Movie Recommendation System

## Overview
This project develops a personalized movie recommendation system using the Netflix Prize Dataset.

## Implemented Models

- Item-Based Collaborative Filtering
- Singular Value Decomposition (SVD)

## Dataset Statistics

- Users: 470,758
- Movies: 4,499
- Ratings: 24,053,764
- Sparsity: 98.86%

## Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAP@10 (Mean Average Precision at 10)

## Results

| Model | RMSE |
|---------|---------|
| Item-Based CF | 1.12 |
| SVD | 0.98 |

MAP@10 (SVD): 0.7615

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Surprise

## Project Structure

- EDA
- Item-Based Collaborative Filtering
- SVD Model
- Model Comparison
- Recommendation Generation

## Conclusion

SVD achieved the best performance with lower prediction error and strong ranking quality, demonstrating the effectiveness of matrix factorization techniques for large-scale recommendation systems.