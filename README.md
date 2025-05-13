# Candidate Test 2022 - Political Data Analysis 🇩🇰

This project analyzes Danish political data collected from the 2022 Candidate Test conducted by two major broadcasters: DR and TV2. The dataset includes politicians' responses on a range of political questions, scaled from -2 to 2, along with demographic and affiliation metadata.

## 📂 Data Sources

The project uses the following Excel datasets:

- `alldata.xlsx` – Combined responses from both DR and TV2.
- `drdata.xlsx` – Responses from DR.
- `drq.xlsx` – Question metadata from DR.
- `tv2data.xlsx` – Responses from TV2.
- `tv2q.xlsx` – Question metadata from TV2.
- `electeddata.xlsx` – Filtered dataset of candidates elected to parliament.

> ⚠️ Note: Some elected members (including Mette Frederiksen and Lars Løkke) did not participate in the candidate test.

## 🧠 Analysis Goals

The analysis focuses on:

- 🧮 **Principal Component Analysis (PCA)**:
  - Dimensionality reduction to identify ideological patterns.
  - Loadings used to interpret most influential political questions.
- 📊 **Clustering**:
  - K-Means, DBSCAN, and Hierarchical clustering of candidates.
  - Visualize ideological similarity across parties and candidates.
- 📈 **Party Positioning**:
  - Average score per party per question.
  - Horizontal bar plots to visualize party stances.
- 🔍 **Elected Candidates**:
  - Highlight alignment and variance among elected officials.
  - Cohesion metric within each party based on Euclidean distances.

## 🔧 Technologies & Libraries

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📎 How to Run

1. Clone the repo or open the notebook in JupyterLab or VSCode.
2. Convert the '.xlsx' files to '.csv'.
3. Place all `.csv` files in the same directory.
4. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
