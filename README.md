# Seeds Data Visualization
A comprehensive data visualization and analysis project focused on the UCI Seeds dataset, exploring the geometric properties of wheat kernels from three different varieties using Python and various data science libraries.
# 📊 Project Overview
This project provides an in-depth analysis and visualization of the Seeds dataset, which contains measurements of geometrical properties of kernels belonging to three different varieties of wheat: Kama, Rosa, and Canadian. The dataset was created using soft X-ray techniques to analyze the internal kernel structure non-destructively.
# 🌾 Dataset Information
The Seeds dataset contains 210 instances (70 for each wheat variety) with 7 continuous attributes:

- Area - Area of the kernel
- Perimeter - Perimeter of the kernel
- Compactness - Compactness (4piArea/Perimeter^2)
- Length - Length of kernel
- Width - Width of kernel
- Asymmetry - Asymmetry coefficient
- Groove Length - Length of kernel groove

## Target Classes:

- Class 1: Kama wheat
- Class 2: Rosa wheat
- Class 3: Canadian wheat

# 🎯 Project Objectives

- Exploratory Data Analysis (EDA): Understand the distribution and relationships between different kernel measurements
- Data Visualization: Create comprehensive visualizations to reveal patterns and insights
Statistical Analysis: Perform statistical tests and correlation analysis
- Classification Visualization: Visualize class separability and clustering patterns
Feature Analysis: Identify the most discriminative features for wheat variety classification

# 🛠️ Technologies Used

- Python 3.x
- Pandas - Data manipulation and analysis
- NumPy - Numerical computing
- Matplotlib - Static plotting and visualization
- Seaborn - Statistical data visualization
- Plotly - Interactive visualizations
- Scikit-learn - Machine learning utilities and preprocessing
- Colab Notebook - Interactive development environment

# 📁 Project Structure
```bash
Seeds-Data_Visualization/
│
├── data/
│   ├── seeds.csv                 # Raw dataset
│   └── seeds_processed.csv       # Cleaned and processed data
│
├── notebooks/
│   ├── 01_exploratory_analysis.ipynb    # EDA and initial exploration
│   ├── 02_data_visualization.ipynb      # Comprehensive visualizations
│   ├── 03_statistical_analysis.ipynb   # Statistical tests and analysis
│   └── 04_feature_analysis.ipynb       # Feature importance and selection
│
├── src/
│   ├── data_preprocessing.py     # Data cleaning and preprocessing
│   ├── visualization_utils.py    # Custom visualization functions
│   └── statistical_analysis.py  # Statistical analysis utilities
│
├── visualizations/
│   ├── distribution_plots/       # Histograms, box plots, violin plots
│   ├── correlation_analysis/     # Correlation matrices and heatmaps
│   ├── scatter_plots/           # 2D and 3D scatter plots
│   └── classification_plots/    # Class separation visualizations
│
├── requirements.txt             # Python dependencies
├── README.md                   # Project documentation
└── LICENSE                     # License information
```
# 🚀 Getting Started
### Prerequisites
Ensure you have Python 3.7+ installed on your system.
Installation

### Clone the repository:
bashgit clone https://github.com/tanutripathi1810/Seeds-Data_Visualization.git
cd Seeds-Data_Visualization

### Create a virtual environment (recommended):
bashpython -m venv seeds_env
source seeds_env/bin/activate  # On Windows: seeds_env\Scripts\activate

### Install required packages:
bashpip install -r requirements.txt

# 📈 Key Visualizations
This project includes various types of visualizations:
## Distribution Analysis

Histograms showing the distribution of each geometric property
Box plots comparing distributions across wheat varieties
Violin plots revealing distribution shapes and density

## Correlation Analysis

Correlation heatmaps showing relationships between features
Pair plots for comprehensive feature comparison
Scatter plot matrices for multivariate analysis

## Classification Insights

2D scatter plots colored by wheat variety
3D visualizations for three-dimensional feature relationships
Principal Component Analysis (PCA) plots for dimensionality reduction

## Statistical Visualizations

ANOVA results comparing means across groups
Feature importance rankings
Class separability analysis

# 🔍 Key Findings
Through comprehensive analysis and visualization, this project reveals:

- Feature Correlations: Strong correlations between certain geometric properties
- Class Separability: Clear patterns distinguishing the three wheat varieties
- Most Discriminative Features: Identification of features that best separate wheat types
- Distribution Patterns: Understanding of how measurements vary within and between varieties

# 📊 Sample Insights

Compactness and Length show significant differences between wheat varieties
Area and Perimeter are highly correlated as expected
Canadian wheat tends to have distinct geometric properties compared to Kama and Rosa
Asymmetry and Groove Length provide unique discriminative power

# 🤝 Contributing
Contributions are welcome! Please feel free to:

Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

# 📝 Future Enhancements

Interactive Dashboards: Create web-based interactive visualizations
Machine Learning Models: Implement classification algorithms
Advanced Analytics: Time series analysis if temporal data becomes available
Comparative Studies: Compare with other grain datasets

# 📚 References

UCI Machine Learning Repository - Seeds Dataset
Original research on wheat kernel analysis using X-ray techniques
Various data visualization and statistical analysis methodologies

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
# 👤 Author
Tanu Tripathi

GitHub: @tanutripathi1810
Email: tripathitanu02@gmail.com

# 🙏 Acknowledgments

UCI Machine Learning Repository for providing the Seeds dataset
The research community for wheat kernel analysis methodologies
Open-source Python data science community for excellent tools and libraries


### ⭐ If you found this project helpful, please consider giving it a star!
