
# 🧬 Classification of Mice Based on Protein Expression

Welcome to the **Classification of Mice Based on Protein Expression** project! 
## 📊 Project Overview
This project aims to classify mice with and without Down Syndrome using protein expression levels. This research is significant as it can provide insights into the molecular mechanisms underlying Down Syndrome, potentially guiding future research.
This project involved several key steps to ensure the best performance of our models:

### 1. **Preprocessing 🛠️**

- **Data Cleaning**: We began by cleaning the dataset, handling missing values, and normalizing protein expression levels to ensure consistency.
- **Balancing the Dataset**: To address class imbalance, we employed techniques such as SMOTE (Synthetic Minority Over-sampling Technique).

### 2. **Exploratory Data Analysis (EDA) 🔍**

- **Visualizations**: We used various plots to explore the distribution of protein expression levels, the correlation between different proteins, and the differences between mice with and without Down Syndrome.
- **Statistical Analysis**: We conducted statistical tests to identify significant differences in protein expression between the two groups.

### 3. **Feature Selection 🧠**

- **Correlation Matrix**: We utilized a correlation matrix to identify and remove highly correlated features that could lead to multicollinearity.
- **Feature Importance**: Using methods like Random Forest and Recursive Feature Elimination (RFE), we selected the most relevant features for our classification models.

### 4. **Model Training 🤖**

We trained and compared several models to find the best one for our classification task:

- **Random Forest (RF) 🌲**: A robust ensemble model that can handle non-linear data and interactions between features.
- **Support Vector Machine (SVM) 📈**: A powerful classifier that works well with high-dimensional data.
- **Neural Networks (NN) 🧠**: A deep learning approach that captures complex patterns in the data.

### 5. **Fine-Tuning 🎛️**

- **Hyperparameter Tuning**: We fine-tuned the models using GridSearchCV to find the optimal parameters for each classifier.
- **Cross-Validation**: To ensure the models' robustness, we applied repeated cross-validation, which provided a more reliable estimate of model performance.

### 6. **Evaluation 📊**

- **Performance Metrics**: We evaluated the models using accuracy, precision, recall, and F1-score, achieving an accuracy of 99.78% with our best-performing model.
- **ROC-AUC Curve**: The ROC-AUC curve was plotted to visualize the trade-off between true positive rate and false positive rate across different threshold settings.

## 🔗 Conclusion

The project successfully classified mice with and without Down Syndrome based on protein expression levels, demonstrating the potential of machine learning in biomedical research. The insights gained from this analysis could help in understanding the molecular basis of Down Syndrome and pave the way for future studies.
