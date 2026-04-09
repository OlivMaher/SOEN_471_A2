# SmartCart
SmartCart implements the full pipeline of a product recommendation system

## Project Structure

### Part 1: Data preprocessing
- Loads both CSVs
- Constructs a user-item matrix
- Aggregates user behavior by category

### Part 2: User-based Collaborative Filtering
- Cosine similarity between users
- Recommends top-N products from the most similar user in which the target user hasn't rated
- Evaluates recommendations with Preision@K, Recall@K, MAP@K, and Coverage

### Part 3: Associate Rule Mining
- Coverts user-product ratings into a one-hot matrix
- Mines frequent itemsets
- Generates association rules

### Part 4: Visualization
- User similarity heatmap
- Bar chart of top 10 frequent itemsets

## Requirements
 
```
pandas
scikit-learn
mlxtend
seaborn
matplotlib
```

Download requirements:
 
```
pip install pandas scikit-learn mlxtend seaborn matplotlib
```



