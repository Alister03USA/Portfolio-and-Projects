Data Science and AI Projects Description

1. Marketing Campaign Analysis
- Data Analysis, Visualization, and applying Machine Learning on the Marketing Campaign Dataset: https://www.kaggle.com/datasets/whenamancodes/customer-personality-analysis
  
2. Image Classification for differentiating African and Asian Elephants
- Image Classification using CNNs and Keras: Apply the Xception Model to train (940 Elephant images) and test (188 Elephant images) with an accuracy of 0.87

3. S&P500 Stock Prediction Using Machine Learning
- Developed a machine learning pipeline to predict short-term movements in the S&P 500 index using historical market data. The project involved:
    - Data Engineering: Created features including daily Open, High, Low, Close, Volume, and the subsequent day's price to establish a binary target variable for upward price movement.
    - Model Development: Implemented a Random Forest Classifier with tuned hyperparameters (n_estimators=100, min_samples_split=100) to forecast daily market trends.
    - Backtesting & Evaluation: Designed a rolling backtesting framework to iteratively train and test the model on sequential periods, ensuring robust performance assessment.
    - Achieved measurable precision in predicting daily upward movement (only 55% accuracy - need further improvement).
    - Visualization & Insights: Combined actual vs. predicted outcomes to visually analyze model performance and assess prediction accuracy over time.
