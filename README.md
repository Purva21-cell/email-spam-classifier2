# email-spam-classifier2
#  Email Spam Classifier

A Machine Learning project that identifies whether an SMS message is **Spam** or **Ham (Legitimate)** using Natural Language Processing (NLP), TF-IDF vectorization, and Logistic Regression.

##  Project Overview

The Email Spam Classifier is a machine learning-based application designed to classify text messages into two categories: spam and legitimate messages.

The project uses text preprocessing techniques and TF-IDF (Term Frequency–Inverse Document Frequency) to convert text into numerical features. A Logistic Regression model is then trained to identify spam patterns and classify messages.

The project also includes model evaluation using performance metrics and visualizations to analyze the effectiveness of the trained classifier.

##  Objectives

- Build a machine learning model to detect spam messages.
- Perform text preprocessing and cleaning.
- Convert textual data into numerical features using TF-IDF.
- Train a Logistic Regression classification model.
- Evaluate model performance using standard classification metrics.
- Visualize results using a confusion matrix and ROC curve.

##  Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Development environment |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Scikit-learn | Machine learning |
| TF-IDF | Text feature extraction |
| Logistic Regression | Classification algorithm |
| Matplotlib | Data visualization |
| Joblib | Model serialization |

##  Dataset

The project uses the **SMS Spam Collection Dataset** from the UCI Machine Learning Repository.

The dataset contains text messages categorized into two classes:

- **Ham:** Legitimate messages.
- **Spam:** Unwanted or fraudulent messages.

Dataset source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

##  Project Workflow

1. **Data Collection:** Load the SMS Spam Collection dataset.
2. **Data Preprocessing:** Clean and normalize text messages.
3. **Feature Extraction:** Convert text into numerical features using TF-IDF.
4. **Model Training:** Train a Logistic Regression classifier.
5. **Model Testing:** Evaluate the trained model using test data.
6. **Performance Evaluation:** Calculate accuracy, precision, recall, and F1-score.
7. **Visualization:** Generate a confusion matrix and ROC curve.
8. **Reporting:** Summarize evaluation results and suggest improvements.

##  Machine Learning Algorithm

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for classification problems.

In this project, it predicts whether a message belongs to the Spam or Ham category based on the numerical features extracted from its text.

### TF-IDF Vectorization

TF-IDF converts text messages into numerical representations based on the importance of words within the dataset.

This allows the machine learning model to process and learn patterns from textual data.

##  Model Evaluation

The trained model is evaluated using the following metrics:

| Metric | Description |
|---|---|
| Accuracy | Measures overall prediction correctness. |
| Precision | Measures how many predicted spam messages are actually spam. |
| Recall | Measures how many actual spam messages are correctly identified. |
| F1-Score | Balances precision and recall. |
| ROC-AUC | Measures the model's ability to distinguish between the two classes. |

### Visualizations

The project generates:

- **Confusion Matrix:** Displays correct and incorrect classifications.
- **ROC Curve:** Visualizes the relationship between the true positive rate and false positive rate.

The actual evaluation scores and generated plots are available in the project notebook and output files.

##  Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/email-spam-classifier.git
```

### 2. Navigate to the project directory

```bash
cd email-spam-classifier
```

### 3. Install dependencies

```bash
pip install pandas numpy scikit-learn matplotlib joblib jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run the notebook

Open `Email_Spam_Classifier_Final.ipynb` and execute the cells sequentially.

Ensure that the dataset and saved model are available at the paths expected by the notebook.

##  Future Improvements

- Experiment with advanced NLP techniques.
- Compare multiple machine learning algorithms.
- Perform hyperparameter tuning.
- Improve feature extraction using n-grams.
- Evaluate performance on additional unseen datasets.
- Develop a simple web application for real-time spam detection.

##  Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing.
- Text preprocessing and feature extraction.
- Supervised machine learning.
- Model training and evaluation.
- Data visualization.
- Python-based machine learning workflows.

##  Author

**Purva Ghate**

Electronics and Telecommunication Engineering Student

GitHub: https://github.com/Purva21-cell

---

⭐ If you find this project useful, consider giving the repository a star!
