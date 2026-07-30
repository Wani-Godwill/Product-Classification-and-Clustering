
# Text Mining: Product Classification and Clustering

## Overview

This project explores **supervised** and **unsupervised** text mining techniques on the **PriceRunner Aggregate** dataset. Product titles are transformed into numerical features using **TF-IDF** and analyzed through **classification** and **clustering** to automatically categorize products and discover hidden patterns in unlabeled data. :contentReference[oaicite:0]{index=0}

## Project Tasks

### 1. Text Classification
A supervised learning approach to predict product categories from product titles.

- Text preprocessing and cleaning
- TF-IDF feature extraction
- Logistic Regression
- Random Forest
- Performance evaluation using Accuracy, Precision, Recall, F1-score, and Confusion Matrix

### 2. Text Clustering
An unsupervised learning approach to group similar product titles without using labels.

- Text preprocessing
- TF-IDF vectorization
- K-Means clustering
- Cluster visualization using Truncated SVD
- Evaluation using Silhouette Score and qualitative cluster analysis :contentReference[oaicite:1]{index=1}

## Dataset

- **PriceRunner Aggregate Dataset**
- **35,311** product titles
- **10 product categories**, including CPUs, Mobile Phones, TVs, Cameras, Microwaves, Dishwashers, Washing Machines, Fridges, Freezers, and Fridge Freezers. :contentReference[oaicite:2]{index=2}

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results

- **Classification:** Logistic Regression and Random Forest achieved approximately **95% accuracy**, demonstrating strong performance for automated product categorization.
- **Clustering:** K-Means identified meaningful product groups, providing insights into the underlying structure of the dataset despite the challenges of high-dimensional text data. :contentReference[oaicite:3]{index=3}

## Repository Structure

```text
Text-Mining-Project/
│
├── README.md
├── text_classification.ipynb
├── text_clustering.ipynb
└── Project Report.pdf
```

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the notebooks in Jupyter Notebook or VS Code.
4. Run `text_classification.ipynb` for the classification task.
5. Run `text_clustering.ipynb` for the clustering task.

