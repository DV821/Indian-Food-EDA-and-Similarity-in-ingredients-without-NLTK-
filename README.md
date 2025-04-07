# 🍛 Indian Food EDA & Recipe Similarity

This project explores a dataset of Indian food recipes using exploratory data analysis (EDA) and computes recipe similarity — all without using the `nltk` library.


## 📊 Dataset

The dataset `indian_food.csv` contains a variety of Indian recipes with attributes such as:

- **Name**
- **Ingredients**
- **Cuisine**
- **Course (e.g., Snack, Main Course)**
- **Prep and Cook Time**
- **Dietary Information** (Vegan, Vegetarian, etc.)
- **Flavor Profile** (Spicy, Sweet, etc.)

## 🔍 Features & Analysis

- Descriptive statistics and visualizations of ingredients, courses, and cuisines.
- Ingredient frequency and word clouds.
- Recipe similarity based on ingredient overlap using custom NLP logic (no `nltk`).
- Identification of unique and common recipes.
- Clustering similar recipes using cosine similarity.

## 🧪 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/indian-food-eda.git
    cd indian-food-eda
    ```

2. Install required libraries:
    ```bash
    pip install pandas matplotlib seaborn scikit-learn
    ```

3. Open the notebook:
    ```bash
    jupyter notebook indian-food-eda-and-similarity-without-nltk.ipynb
    ```

## 📈 Sample Visualizations

- Ingredient Word Clouds
- Distribution of Dishes by Cuisine and Course
- Heatmap of Recipe Similarity

## 📌 Notes

- This version avoids using the `nltk` library by leveraging basic Python string manipulation and `scikit-learn`'s `CountVectorizer`.
- The dataset may require minimal cleaning before use depending on your setup.


Enjoy exploring the rich diversity of Indian cuisine! 🇮🇳
