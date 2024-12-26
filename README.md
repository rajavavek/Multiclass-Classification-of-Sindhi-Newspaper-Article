# Multiclass-Classification-of-Sindhi-Newspaper-Article
Multiclass Classification of Sindhi Newspaper Article Using Deep Learning Models
Deep Learning approach for multiclass classification of Sindhi newspaper articles. The proposed model leverages deep learning models to learn features from text data. The models is trained and evaluated on a dataset of Sindhi newspaper articles. The results demonstrate the effectiveness of the proposed approach for Sindhi text classification, paving the way for applications in news analysis and information retrieval.

Dataset: https://github.com/rajavavek/SindMT/blob/main/Articles%20Dataset.csv

![image](https://github.com/user-attachments/assets/9a0dcea9-0fb5-4184-aab9-657f605f3ad1)

# CNN Model Classification Report

| Category       | Precision | Recall  | F1-Score | Support |
|----------------|-----------|---------|----------|---------|
| Entertainment  | 0.969027  | 0.948052 | 0.958425 | 231     |
| Sports         | 0.976667  | 0.970199 | 0.973422 | 302     |
| Technology     | 0.939189  | 0.985816 | 0.961938 | 141     |
| **Accuracy**   | **0.965875** | **0.965875** | **0.965875** | **0.965875** |


# RNN Model Classification Report

| Category       | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Entertainment  | 0.54      | 0.45   | 0.49     | 231     |
| Sports         | 0.64      | 0.70   | 0.67     | 302     |
| Technology     | 0.91      | 0.95   | 0.93     | 141     |
| **Accuracy**   | **-**     | **-**  | **0.67** | **674** |



# LSTM Model Classification Report

| Category       | Precision | Recall  | F1-Score | Support |
|----------------|-----------|---------|----------|---------|
| Entertainment  | 0.968750  | 0.939394 | 0.953846 | 231     |
| Sports         | 0.963576  | 0.963576 | 0.963576 | 302     |
| Technology     | 0.932432  | 0.978723 | 0.955017 | 141     |
| **Accuracy**   | **-**     | **-**    | **0.958457** | **674** |


# Hybrid Model Classification Report

| Category       | Precision | Recall | F1-Score | Support |
|----------------|-----------|--------|----------|---------|
| Entertainment  | 0.96      | 0.94   | 0.95     | 231     |
| Sports         | 0.96      | 0.97   | 0.97     | 302     |
| Technology     | 0.95      | 0.97   | 0.96     | 141     |
| **Accuracy**   | **-**     | **-**  | **0.96** | **674** |
| **Macro Avg**  | 0.96      | 0.96   | 0.96     | 674     |
| **Weighted Avg** | 0.96    | 0.96   | 0.96     | 674     |


The classification performance of various models on the dataset shows promising results. The CNN model achieved 96.59% accuracy, followed closely by the LSTM at 95.85% and the HyBrefd model at 96%. The RNN model lagged, reaching only 67% accuracy. Overall, deep learning models demonstrated high precision, recall, and F1-scores, showcasing their effectiveness.

