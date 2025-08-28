# Recommendation System: IBM Community

In the **IBM Watson Studio**, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.

---

## 🚀 Getting Started

For this project, we will analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles according to their interests.

In order to determine which articles to show to each user, we will be performing a study of the data available on the IBM Watson Studio platform.:

- Exploratory Data Analysis.  
- Rank Based Recommendations.  
- User-User Based Collaborative Filtering.  
- Evaluate model performance using appropriate metrics.
- Content Based Recommendations.
- Matrix Factorization.

---

## 📦 Dependencies

The project requires the following libraries:

- [scikit-learn](https://scikit-learn.org/stable/)  
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.com/)  
- [spaCy](https://spacy.io/)  
- [Jupyter Notebook](https://jupyter.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

---

## 📦 Project Workflow

- I. Exploratory Data Analysis

Before making recommendations of any kind, we will need to explore the data for the project. We will dive in to see what we can find. There are some basic, required questions to be answered about the data we are working with throughout the notebook.

- II. Rank Based Recommendations

To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

- III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

- IV. Content Based Recommendations

Since we are provided some content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using NLP, we'll come up with a simple method to cluster similar articles together so we can recommend related content that the user may have already interacted with.

- V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using this decomposition, we will get an idea of how well we can predict new articles an individual might interact with. We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.

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
