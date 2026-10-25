# Text Classification Battle — Compare, Analyze and Defend

## 📌 Project Overview
This project compares four machine learning algorithms for text classification using TF-IDF feature extraction. The models are evaluated using multiple performance metrics to identify the most suitable classifier.

## 📓 Project Notebook

🚀 **[Open the Project in Google Colab](https://colab.research.google.com/drive/1V12akYYOOA8BNO5_b21Ks7CdszcqTLWJ#scrollTo=dd2Aa-GQ4jyz)**

The notebook includes data exploration, feature extraction, model training, evaluation, confusion matrices, visualizations, and the what-if experiment.

## 📊 Dataset
**Dataset:** 20 Newsgroups

Four selected categories:
- Computer Graphics
- Baseball
- Space
- Politics

The dataset is used to classify text documents into their respective categories.

## 🤖 Machine Learning Algorithms
1. Decision Tree
2. K-Nearest Neighbors (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naive Bayes

## ⚙️ Methodology
1. Load and explore the dataset.
2. Examine the distribution of documents across categories.
3. Split the dataset into training and testing sets using an 80:20 ratio.
4. Convert text into numerical features using TF-IDF.
5. Train and test the four machine learning models.
6. Evaluate the models using classification metrics.
7. Compare the confusion matrices and model performance.
8. Conduct a what-if experiment by comparing unigram features with unigram-and-bigram features.

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- Macro F1-score
- Confusion matrix

## 🧪 What-If Experiment
The experiment investigates how adding bigram features to unigram TF-IDF affects the performance of each classifier. The results are compared using macro F1-score.

## 🛠️ Technologies Used
- Python
- Google Colab
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## 🏆 Results
In the original unigram experiment, **Multinomial Naive Bayes achieved approximately 90.48% accuracy and a macro F1-score of 0.9032**.

The notebook and CSV files contain the detailed results for all four classifiers and the what-if experiment.

## 📁 Project Files

| File | Description |
|---|---|
| `IR_Task_2_RA2411026050068.ipynb` | Complete project implementation |
| `results.csv` | Original model evaluation results |
| `what_if_results.csv` | Results from the bigram experiment |
| `what_if_comparison.csv` | Comparison of unigram and bigram F1-scores |
| `model_comparison.png` | Model performance comparison |
| `confusion_matrix_comparison.png` | Confusion matrices for the four classifiers |
| `what_if_analysis.png` | Visualization of the what-if experiment |
| `class_distribution (1).png` | Dataset class distribution |

## ▶️ How to Run
1. Open the notebook using the Google Colab link above.
2. If necessary, upload the notebook to your Google Drive or open the GitHub notebook in Colab.
3. Run the cells sequentially from top to bottom.
4. Review the evaluation metrics, confusion matrices, graphs, and final conclusion.

