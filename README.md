# sc5010-introduction-to-data-analysis
# Pima Indians Diabetes Classification & Clustering
## TEL2 Group 1
| Name           | Matric Number |
|----------------|---------------|
| Brad Lee                 | U2130355E      |
| Cheng Jun Long Brandon   | U2222813C      |
| Nicolas Chan Han Hui     | U2230785E      |
| Nigel Max Wee Yaohan     | U2221718B      |


## Objective
<p align="justify"> 
To develop and fine-tune machine learning models for predicting the likelihood of diabetes using the Pima Indians Diabetes dataset. The objective is to identify key clinical features contributing to diabetes risk and evaluate various classification algorithms, including ensemble methods. Additionally, by leveraging interpretability tools such as SHAP and unsupervised clustering techniques, we aim to uncover meaningful patient groupings and enable targeted risk stratification. The goal is to create a robust, interpretable predictive system that can support early diagnosis and personalised healthcare interventions. 
</p>

## Dataset
</p>
Link: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database <br>
Please ensure that the dataset used is in the correct folder(s) as seen in the directory tree
</p>

## Directory Tree

``` 
.
├── diabetes-prediction.ipynb
├── data/
│   └── diabetes.csv
├── requirements.txt
├── README.md
├── Project_Report_Group_TEL2GROUP1.docx
├── Project_Presentation_Group_TEL2GROUP1.pptx
├── sc5010 project assignment.pdf
└── clustering/
    ├── clustering.ipynb
    ├── diabetes.csv
    └── preprocessed_diabetes.csv
```

## Step 1. Clone GitHub repository 
```
git clone https://github.com/nigelmaxwee/sc5010-introduction-to-data-analysis
cd sc5010-introduction-to-data-analysis
```

## Step 2. Ensure Python is version 3.12
This is mainly for compatibility with packages <br>
Download link: https://www.python.org/downloads/release/python-3124/
```
python --version
```

## Step 3. Create a virtual environment
```
python -m venv venv
```

## Step 4. Install dependencies
```
pip install -r requirements.txt
```

## Runtime

- **Total execution time**: ~5 minutes  
  (on a standard desktop with Ryzen 5, 32GB RAM)
