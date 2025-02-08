# Breast Cancer Classification using Random Forest

## Overview
This project implements a machine learning solution for breast cancer diagnosis using the Wisconsin Breast Cancer Dataset. The model utilizes a Random Forest Classifier to categorize breast tumors as either malignant or benign based on cellular characteristics derived from image analysis.

## Dataset
The project uses the Breast Cancer Wisconsin (Diagnostic) dataset from UCI Machine Learning Repository:
- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**: 30 numeric features computed from digitized images
- **Classes**: Binary (Malignant/Benign)
- **Samples**: 569 total instances

## Requirements
```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## Installation
1. Clone the repository:
```bash
git clone [https://github.com/Sramieni/Breast-Cancer-Classification-Using-Random-Forest]
cd breast-cancer-classification-USing-Random-Forest
```

2. Install required packages:
```bash
pip install -r requirements.txt
```


## Model Performance
The Random Forest classifier achieves:
- Accuracy: 95.61%
- Precision: 95% (Malignant), 96% (Benign)
- Recall: 93% (Malignant), 97% (Benign)
- F1-Score: 94% (Malignant), 97% (Benign)

## Feature Importance
Key features for classification:
1. Worst perimeter
2. Worst area
3. Worst concave points

## Visualizations
The project includes several visualizations:
- Class distribution plots
- Confusion matrix heatmap
- Feature importance bar charts
- Performance metrics visualization



## Acknowledgments
- UCI Machine Learning Repository for providing the dataset
- scikit-learn documentation and community
- Wisconsin Diagnostic Breast Cancer (WDBC) dataset creators

## Contact
[Ramineni Sesha Sai ]
Project Link: [https://github.com/Sramieni/Breast-Cancer-Classification-Using-Random-Forest]
