# Predicting-CVD-Risk-and-Outcomes-with-RNN
This project uses recurrent neural networks to predict the risk factors and outcomes of cardiovascular diseases based on medical data. It achieves an impressive AUC score of 0.9 on the test set, and provides data-driven recommendations for improving the clinical decision making.

# Predicting CVD Risk and Outcomes with RNNs: A Data-Driven Approach

This repository contains the code and data for a freelance project I did for Sarita Charkha Ma'am, an assistant professor at G. H. Raisoni Institute of Engineering and Business Management, in March 2023 - May 2023. The goal of the project was to use machine learning to predict the risk factors and outcomes of cardiovascular diseases (CVD), such as heart attack, stroke, and death, based on medical data.

## Data

The data used for this project was obtained from various sources, such as electronic health records, lab tests, and surveys. The data contained information about the patients' demographics, medical history, lifestyle, symptoms, diagnosis, treatment, and follow-up. The data was cleaned, preprocessed, and split into train, validation, and test sets.

## Model

The model used for this project was a recurrent neural network (RNN) with long short-term memory (LSTM) cells. The RNN model was able to capture the temporal dependencies and patterns in the data, and learn from the sequential nature of the medical events. The model was trained and tuned using TensorFlow and Keras, and applied to predict the risk and outcomes of CVD, such as low, medium, high, or very high risk, and alive, dead, or disabled outcome.

## Evaluation

The model's performance was evaluated using various metrics, such as accuracy, precision, recall, F1-score, ROC curve, and AUC score. The model achieved an impressive AUC score of 0.9 on the test set, indicating a high ability to discriminate between different classes of risk and outcomes. The model also outperformed the baseline models, such as logistic regression and random forest, on all the metrics.

## Results and Recommendations

The results and recommendations of the project were presented to the client using data visualisation tools, such as Matplotlib, Seaborn, and Plotly. The results showed the model's predictions, the feature importance, and the error analysis. The recommendations included suggestions for improving the data quality, the model performance, and the clinical decision making. The client was satisfied with the project outcome and appreciated the data-driven approach for predicting CVD risk and outcomes.
