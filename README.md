# Recommendation System: IBM Community

In the **IBM Watson Studio**, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.

---

## 🚀 Getting Started

Use the provided dataset to train and evaluate your prediction model. Your pipeline should:

- Handle **numerical**, **categorical**, and **text** features appropriately.  
- Incorporate proper preprocessing steps for each feature type.  
- Train a classifier to predict product recommendation.  
- Evaluate model performance using appropriate metrics.  

---

## 📦 Dependencies

The project requires the following libraries:

- [scikit-learn](https://scikit-learn.org/stable/)  
- [pandas](https://pandas.pydata.org/)  
- [spaCy](https://spacy.io/)  
- [Jupyter Notebook](https://jupyter.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

---

## 📦 Project Workflow

Exploratory Data Analysis (EDA)

- Distribution of numeric features (Age, Feedback Count).

- Missing value analysis.

- Word frequency clouds for reviews.

Pipeline & Preprocessing

- Numeric: imputation (median) + scaling.

- Categorical: imputation (most frequent) + encoding.

- Text: TF-IDF, character counts.

Model Training & Evaluation

- Base model: RandomForestClassifier.

- Evaluation: accuracy score.

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
python -m pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

---

## 📊 Results

- Accuracy    : ~ 0.8710

- Precision   : ~ 0.8661

- Recall      : ~ 0.8710

- F1-Score    : ~ 0.8525

---

## License

[License](LICENSE.txt)
