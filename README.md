# VortexTech AI/ML Internship — Week 3

Welcome to Week 3 of the VortexTech AI/ML Internship! This week focuses on two core machine learning paradigms: Regression and Clustering. We predict continuous outcomes and find hidden structures in data without labels.

## Datasets
- **California Housing Dataset (Regression):** Predicts median house value using 8 numeric features (20,640 rows). No external download needed; this dataset ships with scikit-learn.
- **Iris Dataset (Clustering):** A classic dataset from which we isolate just two features (petal length and petal width) to cluster the data into groups. No external download needed; this dataset ships with scikit-learn.

## Approach Summary
- **Regression:** Loaded California Housing data → Applied feature engineering (`RoomsPerHousehold`, `BedroomRatio`) → Trained a Linear Regression baseline and a Random Forest main model → Compared models using RMSE, MAE, and R2.
- **Clustering:** Loaded Iris petal features → Applied feature scaling → Used the Elbow method to find optimal clusters (k=3) → Trained a K-Means model → Revealed true species labels for final validation.

## Results Table
| Model              | RMSE | MAE  | R2   |
|--------------------|------|------|------|
| Linear Regression  | 0.729170 | 0.526041 | 0.594257 |
| Random Forest      | 0.512636 | 0.332464 | 0.799455 |

## How to Run
1. Clone the repository
2. Create and activate a virtual environment: `python -m venv venv`
3. Activate the environment (`.\venv\Scripts\activate` on Windows or `source venv/bin/activate` on Mac/Linux)
4. Install dependencies: `pip install -r requirements.txt`
5. Run the notebook: `jupyter notebook regression_and_clustering.ipynb`

## Repository Structure
```
vortextech-aiml-week3/
├── .gitignore
├── README.md
├── regression_and_clustering.ipynb
├── requirements.txt
```

Mohid Saleem — VortexTech AI/ML Internship, Week 3
