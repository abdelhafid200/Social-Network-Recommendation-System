# Social Network Recommendation System

## Introduction
The **Social Network Recommendation System** is a machine learning-based system designed to provide personalized recommendations for connections in a social network. By leveraging graph-based techniques and predictive modeling, this system suggests the most relevant potential connections for users based on probabilistic link prediction.

## Features
- **Graph-based link prediction**: Uses network structure to predict potential connections.
- **Machine learning models**: Employs trained models to assess the likelihood of new connections.
- **Feature engineering**: Extracts relevant features from the graph for improved predictions.
- **Recommendation generation**: Provides top recommendations for users based on computed probabilities.
- **Evaluation and visualization**: Displays performance metrics and graphical insights.
- **Results export**: Saves recommendations and related metrics in CSV format.

## Implementation Details
### 1. Data Preparation
- Uses a dataset of social network connections.
- Transforms network data into a graph representation.

### 2. Feature Engineering
- Extracts node and edge features such as common neighbors, Jaccard coefficient, and preferential attachment.

### 3. Model Training
- Trains machine learning models (e.g., Logistic Regression, Random Forest..., Neural Networks) on labeled data.
- Selects the best model based on test performance (F1-score, accuracy, precision, recall).

### 4. Recommendation Generation
- Predicts the probability of new connections for a subset of users.
- Selects top recommendations based on computed probabilities.
- Saves recommendations and probability metrics.

### 5. Visualization
- Creates bar charts and box plots to analyze recommendation confidence levels.
- Displays the probability distribution of recommended connections.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Social-Network-Recommendation-System.git
   cd Social-Network-Recommendation-System
   ```

## Future Improvements
- Improve feature selection for better predictions.
- Experiment with deep learning models for link prediction.
- Extend recommendations to community detection and influence analysis.

## Link To Share : 
```
- https://stone-plate-5d7.notion.site/Tutoriel-A-Guide-on-Social-Network-Recommendation-System-1a7f9267b2a580319c03cefc11f42cf6
```
## Author
**ABDELHAFID KHALIL 
Final Year Project Master IAII**



