# Opinion Mining Using Ensemble Learning

This project focuses on opinion mining from hotel customer reviews using an ensemble learning approach combining Support Vector Machine (SVM) and Naive Bayes classifiers. The goal is to classify reviews into Positive, Negative, or Neutral sentiments to help businesses analyze customer feedback more effectively.

---

## Dataset

- **File**: `tripadvisor_hotel_reviews.csv` from Kaggle
- **Description**: Contains text reviews and corresponding ratings for hotel experiences.

### Columns:
- `Review`: Customer’s textual feedback
- `Rating`: Integer value from 1 to 5

---

##  Project Workflow

### 1. Data Loading & Exploration
- Load dataset using `pandas`
- Display shape, structure, and check for missing values

### 2. Sentiment Labeling
- Ratings are converted to sentiments:
  - 1-2 → **Negative**
  - 3 → **Neutral**
  - 4-5 → **Positive**

### 3. Text Preprocessing
- Lowercasing, tokenization, stop word removal
- Vectorization using **TF-IDF**

### 4. Model Building
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- Optionally: Use ensemble learning with models like **VotingClassifier** or **BalancedBaggingClassifier**

### 5. Evaluation
- Metrics: Accuracy, Precision, Recall, F1-Score
- Tools: Confusion Matrix, Classification Report

---

## Tech Stack

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn

### Install dependencies:
pip install pandas scikit-learn numpy matplotlib seaborn

**##How to Run**
Clone this repository.
Place tripadvisor_hotel_reviews.csv in the root folder.
Open and run main.ipynb in Jupyter Notebook or any Python environment.

**Author**
Kiranmai Tirupati
