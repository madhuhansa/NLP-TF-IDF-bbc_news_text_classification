# BBC News Text Classification using TF-IDF

This project is a multi-class text classification task using the **BBC News Classification Dataset**. It compares different machine learning models using **TF-IDF** for feature extraction, with and without text preprocessing.

## 🔧 Technologies Used

- Python
- Scikit-learn
- spaCy
- Pandas, NumPy
- Jupyter Notebook

## 📁 Dataset

The dataset includes 2,225 articles from the BBC news website, categorized into 5 classes:
- business
- entertainment
- politics
- sport
- tech

Dataset source: [Kaggle - BBC News Classification](https://www.kaggle.com/datasets/sunilthite/text-document-classification-dataset)

---

## ✅ Results & Observations

- Achieved **95% accuracy** on test data.
- Preprocessing improves model performance, especially for Naive Bayes.
- Random Forest and Naive Bayes gave the best accuracy.

---

## 📁 Project Files & Folders Explained

| File/Folder | Description |
|-------------|-------------|
| `Model/` | Contains all saved machine learning models using `joblib` for future use or deployment. |
| ├── `knn_model.pkl` | Saved K-Nearest Neighbors (KNN) model with TF-IDF vectorizer pipeline. |
| ├── `multinomial_nb_model.pkl` | Saved Multinomial Naive Bayes (NB) model with TF-IDF vectorizer pipeline. |
| └── `random_forest_model.pkl` | Saved Random Forest Classifier model with TF-IDF vectorizer pipeline. |
| `df_file.csv` | Original cleaned BBC News dataset used for classification. |
| `df_file.ipynb` | Main notebook used for training models, evaluating performance, and saving them. Includes 6 modeling attempts (with/without preprocessing). |
| `tf-idf.ipynb` | Notebook explaining the TF-IDF theory and concept]. |
| `README.md` | Project overview, setup instructions, and explanation of the modeling approach and results. |


---

## 🙌 Credits

Project by Yahan Madhuhansa 
