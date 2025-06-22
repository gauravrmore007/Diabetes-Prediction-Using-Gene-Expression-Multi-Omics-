# 🧬 Type 2 Diabetes Prediction using Gene Expression (Multi-Omics)

This project builds a machine learning model to predict Type 2 Diabetes (T2D) status using gene expression data (microarray). It includes feature selection, preprocessing, model training, and performance visualization.

## 🔍 Dataset
- Source: GEO (NCBI) – Public multi-omics dataset with 234 samples.
- Features: 44,760 gene expression values per sample.
- Labels: Healthy vs. T2D

## ⚙️ Methods Used
- Preprocessing: Standard scaling, label encoding
- Model: Random Forest Classifier (with class imbalance handling)
- Evaluation: Precision, Recall, F1-Score, ROC-AUC
- Visuals:
  - Confusion Matrix
  - ROC Curve
  - Top Gene Importance Plot

## 🏆 Results
- **Precision:** 0.79  
- **Recall:** 1.00  
- **F1-Score:** 0.88  
- **Model interpretation**: via feature importance (Random Forest)

## 📁 Project Structure
├── T2D_pred.ipynb # Main Jupyter notebook
├── data/ # Folder with gene_expression.csv and metadata
└── README.md # You're here

## 📌 Future Work
- Integrate other omics layers (e.g. metabolomics)
- Deploy as a Streamlit dashboard
- Enhance interpretability with SHAP or LIME

## 👨‍💻 Author
Gaurav More
M.S. in Biomedical Informatics @ The Ohio State University  
