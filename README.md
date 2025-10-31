# Evaluating Multi-Class Classifier Performance on the Landsat Dataset via ROC and PRC Analysis

- **Author:** Charukhesh  
- **Roll No:** AE22B028

## 📖 Project Overview

This project provides a comprehensive analysis of machine learning models for the multi-class task of land cover classification using the UCI Landsat Satellite dataset. A diverse suite of nine classifiers was evaluated, spanning from baseline models like Dummy and Naive Bayes to robust individual performers such as Support Vector Machines (SVC), and culminating with high-performance ensembles including Random Forest and XGBoost.

The core of the analysis moves beyond simple accuracy metrics, employing a detailed evaluation based on multi-class Receiver Operating Characteristic (ROC) and Precision-Recall (PRC) curves. Performance was assessed both through macro-averaged curves for a high-level view and through per-class analysis to identify specific model strengths and weaknesses. The result is a holistic comparison that evaluates performance across the full spectrum of decision thresholds, culminating in a justified recommendation of the optimal model for this complex classification problem.

## 📁 Repository Structure

```
DA5401-assignment-7-Charukhesh/
│
├── main.ipynb
├── landSat_dataset/
│   ├── sat.trn
│   └── sat.tst
└── README.md
```

- **main.ipynb**: The main Jupyter notebook containing all code, analysis, visualizations, and conclusions.
- **LandSat_dataset/**: Directory containing the dataset used for analysis.
    - **sat.trn**: The Landsat Satellite training dataset from the UCI ML Repository.
    - **sat.tst**: The Landsat Satellite testing dataset from the UCI ML Repository.
- **README.md**: Project documentation and instructions.

## Dependencies

- Python 3.7+
- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn xgboost
```

## How to Run This Project
1. **Clone the Repository**
    ```bash
    git clone https://github.com/Charukhesh/DA5401-assignment-7-Charukhesh.git
    cd DA5401-assignment-7-Charukhesh
    ```

2. **Dataset**
    Ensure the .trn & .tst files are present in the landSat_dataset/ folder.

3. **Open and Run the Notebook**
    - Open `main.ipynb` in [Jupyter Notebook](https://jupyter.org/) or [VS Code](https://code.visualstudio.com/).
    - Run all cells sequentially to reproduce the analysis and results.