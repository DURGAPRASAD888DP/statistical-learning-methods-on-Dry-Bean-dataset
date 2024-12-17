# statistical-learning-methods-on-Dry-Bean-dataset
Here’s a **README** draft based on your project details:

---

# Dry Bean Dataset: Supervised and Unsupervised Learning

## Project Overview
This project analyzes the **Dry Bean Dataset** using supervised and unsupervised machine learning techniques. Models like **Logistic Regression**, **K-Nearest Neighbors (KNN)**, **K-Means Clustering**, and **Hierarchical Clustering** are implemented and evaluated using metrics such as accuracy, precision, recall, F1-score, and silhouette score.

## Dataset Information
- **Samples**: 13,611  
- **Features**: 16 (mix of real and integer types)  
- **Classes**: 7 bean types (SEKER, BARBUNYA, BOMBAY, CALI, HOROZ, SIRA, DERMASON)

### Key Features
1. **Area**: Total size of the bean zone.
2. **Major/Minor Axis Length**: Longest and perpendicular axes.
3. **Aspect Ratio**: Relationship between major and minor axes.
4. **Eccentricity**: Similarity to an ellipse.
5. Additional shape factors and geometry-related features.

## Data Preprocessing
1. **Null Values**: Replaced using column-wise means.  
2. **Scaling**: Applied **MinMaxScaler** to scale features between 0 and 1.

## Exploratory Data Analysis (EDA)
- **Visualizations**:  
  - Bar plots (class distribution, average area).  
  - Histograms (feature distributions).  
  - Heatmap (correlation matrix).  

## Model Development
### Supervised Learning
1. **Logistic Regression**
   - Accuracy: **87%**
   - Precision, Recall, and F1-score provided for individual classes.

2. **K-Nearest Neighbors (KNN)**
   - Accuracy: **92.14%**
   - Precision: **92.24%**
   - High balanced performance observed.

### Unsupervised Learning
1. **K-Means Clustering**
   - Best silhouette score: **0.66** (clusters = 3).
   - Strong group separations observed.

2. **Hierarchical Clustering**
   - Silhouette score: **0.53**.
   - Moderate cluster separations.

## Results Summary
- **KNN** and **Logistic Regression** performed well in classification tasks.
- **K-Means Clustering** exhibited better cluster quality than **Hierarchical Clustering**.

## Conclusions
The classification models effectively predicted bean classes, while K-Means demonstrated superior clustering performance.

## Dependencies
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## How to Run
1. Clone the repository:  
   ```
   git clone <repo_link>
   cd project_directory
   ```
2. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:  
   ```
   jupyter notebook Team_9_ISL_Project.ipynb
   ```

## Project Files
- **Team_9_ISL_Project.ipynb**: Code for preprocessing, modeling, and evaluation.
- **Dry_Bean_Dataset.xlsx**: Dataset file.
- **Project_Report.pdf**: Detailed analysis and results.

## Authors
Durga Prasad Oduri

---
