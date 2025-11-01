# Customer Satisfaction Prediction

## Objective
Predict customer satisfaction (Satisfied vs Unsatisfied) using ticket data with NLP and time-based features.

## Tools & Libraries
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- NLP: VADER Sentiment Analysis, TF-IDF
- Model: Random Forest Classifier (class_weight = 'balanced')
- Pipeline: ColumnTransformer for numeric, categorical, and text data

## Steps
1. Data Cleaning & Feature Engineering
2. Sentiment extraction from ticket description
3. TF-IDF keyword vectorization
4. Combined model pipeline and training
5. Evaluation using accuracy, precision, recall, and F1-score

## Key Insights
- High response/resolution times lead to lower satisfaction.
- Negative sentiment in description strongly correlates with dissatisfaction.

## Business Recommendation
Prioritize tickets with negative sentiment and long resolution times to improve customer retention.

## Links
- [Google Drive Folder] https://drive.google.com/drive/folders/1abDxlRvS4i3HPtJeFZ_CiCRabceGXlxB?usp=drive_link
