# LinkedIn Job Postings Clustering

This project was developed as part of the **Data Mining 2** course at the Faculty of Mathematics, University of Belgrade.

The goal of the project is to analyze and cluster LinkedIn job postings in order to identify groups of similar jobs based on their characteristics. Using data preprocessing techniques, dimensionality reduction methods, and various clustering algorithms, the project explores patterns connecting job titles, required skills, experience levels, benefits, and company characteristics.

Special attention was given to comparing multiple clustering algorithms and evaluating the quality of the resulting clusters through both quantitative metrics and qualitative interpretation.

## Dataset

The project uses a publicly available dataset from Kaggle:

https://www.kaggle.com/datasets/arshkon/linkedin-job-postings

## Project Structure

```text
linkedin-job-postings-clustering
│
├── data/               # raw and processed datasets
│
├── models/             # saved labels and outputs of the best-performing models
│
├── notebooks/
│   ├── preprocessing_data.ipynb
│   ├── data_analysis.ipynb
│   ├── clustering/
│   ├── analysis_no_title.ipynb
│   └── evaluation.ipynb
│
├── results/            # plots, visualizations and evaluation results
│
├── README.md
└── .gitignore
```

## Documentation

A detailed description of the methodology, experiments, and results can be found in the project report:

**[Project Documentation in Serbian](dokumentacija.pdf)**

## Technologies

The project was implemented in Python using the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

All experiments and analyses were conducted using Jupyter Notebook.

## Author

**Marina Vračarić**

Faculty of Mathematics  
University of Belgrade  
