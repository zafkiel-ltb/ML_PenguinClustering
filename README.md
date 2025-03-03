# Penguin Clustering Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Latest-orange)](https://scikit-learn.org/)
[![pandas](https://img.shields.io/badge/pandas-Latest-green)](https://pandas.pydata.org/)
[![matplotlib](https://img.shields.io/badge/matplotlib-Latest-red)](https://matplotlib.org/)

## 📊 Overview

This project applies machine learning clustering techniques to the Palmer Penguins dataset to identify natural groupings based on physical characteristics. The analysis demonstrates how to preprocess data, perform clustering using K-means and Principal Component Analysis (PCA), and visualize the results.

## 🐧 Dataset

The [Palmer Penguins dataset](https://allisonhorst.github.io/palmerpenguins/) contains measurements for 344 penguins from three species:
- Adelie
- Gentoo
- Chinstrap

Features include:
- Bill length, depth
- Flipper length
- Body mass
- Sex

## 🔧 Setup and Installation

### Requirements

- Python 3.8 or higher
- Required packages: 
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/zafkiel-ltb/ML_PenguinClustering.git
   cd ML_PenguinClustering
   ```

2. Install required packages:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

## 🚀 Usage

### Running the Main Analysis

1. Open and run the Jupyter notebook:
   ```bash
   jupyter notebook ML_PenguinClustering.ipynb
   ```

2. Alternatively, run the script directly:
   ```bash
   python penguin_clustering.py
   ```

### Data Processing Steps

The analysis follows these steps:

1. **Data Loading and Exploration**
   - Load the Palmer Penguins dataset
   - Examine the data structure and missing values
   - Generate descriptive statistics

2. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features

3. **Clustering Analysis**
   - Determine optimal number of clusters using the elbow method
   - Apply K-means clustering
   - Validate results against actual species

4. **Dimensionality Reduction**
   - Apply PCA to reduce features to 2D space
   - Visualize clusters in the reduced space

5. **Results Interpretation**
   - Compare clustering results with actual species
   - Analyze feature importance for each cluster

## 📈 Key Visualizations

The project generates several important visualizations:

- **Correlation Matrix**: Displays relationships between penguin measurements
- **Elbow Plot**: Helps determine the optimal number of clusters
- **PCA Cluster Visualization**: Shows clusters in 2D space
- **Feature Distribution by Cluster**: Compares measurements across different clusters

## 🔍 Key Findings

- The clustering algorithm successfully identifies natural groupings that closely match the three penguin species
- Bill length, bill depth, and flipper length are the most significant features for distinguishing between clusters
- The PCA transformation preserves approximately 85% of the variance with just two components

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available for download.

## 📧 Contact

For questions or feedback, please create an issue in the GitHub repository or contact the repository owner.

---

*This project was created as a learning exercise for unsupervised machine learning techniques.*
