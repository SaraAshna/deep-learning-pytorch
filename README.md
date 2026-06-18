# Deep Learning Projects — Sara Ashna

Hands-on PyTorch projects built while developing machine learning skills for biomedical and cancer data analysis.  
Background: M.Sc. Quantitative and Computational Biosciences (University of Padova) | B.Sc. Molecular Biology.

---

## Projects

| Notebook | Task | Key Skills |
|---|---|---|
| `house_price_regression_pytorch.ipynb` | Regression — tabular data | Custom `nn.Module`, dropout, StandardScaler, MSE/MAE/R² evaluation |
| `santander_binary_classification_pytorch.ipynb` | Binary classification — imbalanced data (Kaggle) | DataLoader, BatchNorm, BCEWithLogitsLoss, ROC/PR curves |
| `overfitting_underfitting_demo.ipynb` | Conceptual demo | Diagnosing overfitting vs underfitting, loss curve interpretation |

---

## Skills Demonstrated

- **PyTorch**: custom `nn.Module`, training loops, GPU support, model saving
- **Data preprocessing**: StandardScaler, SimpleImputer, train/val split, tensor conversion
- **Regularization**: Dropout, BatchNorm, weight decay
- **Evaluation**: MSE, MAE, MAPE, R², accuracy, BCEWithLogitsLoss
- **Tools**: scikit-learn, pandas, matplotlib

---

## Goal

These projects are stepping stones toward applying deep learning to cancer genomics — specifically tabular omics data, gene expression classification, and mutation prediction. My computational biology background (RNA-seq, population genomics, differential expression in R/Bioconductor) combines with these ML skills toward that aim.

---

## Requirements

```
torch>=2.0.0
scikit-learn>=1.3.0
pandas>=2.0.0
numpy>=1.24.0
matplotlib>=3.7.0
torchsummary>=1.5.1
```

Install:
```bash
pip install torch scikit-learn pandas numpy matplotlib torchsummary
```
