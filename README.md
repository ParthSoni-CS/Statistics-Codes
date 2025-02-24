# Statistical Analysis Tools in Python

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive collection of statistical analysis tools and examples implemented in Python, featuring both Jupyter notebooks and Python scripts for various statistical methods.

## 📚 Contents

### Analysis Methods
- **ANOVA Analysis**
  - One-way ANOVA
  - One-way Repeated Measures ANOVA
  - Two-way Mixed ANOVA

- **Clustering & Dimensionality Reduction**
  - DBSCAN Clustering
  - JADE Algorithm Implementation

- **Statistical Testing**
  - Confidence Intervals
  - Correlation Analysis
  - T-tests
  - Regression Analysis

- **Data Processing**
  - Descriptive Statistics
  - Normality Tests & Outlier Detection
  - Signal Detection
  - Data Visualization

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/statistical-analysis-tools.git

# Navigate to project directory
cd statistical-analysis-tools

# Install required packages
pip install -r requirements.txt
```

## 📦 Requirements

- Python 3.7+
- NumPy
- Pandas
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 Usage

Each analysis method is available in two formats:
1. Jupyter Notebook (.ipynb) - For interactive exploration
2. Python Script (.py) - For automation and integration

Example:
```python
from anovas.stats_anova_1wayANOVA import perform_anova
import pandas as pd

# Load your data
data = pd.read_csv('your_data.csv')

# Perform one-way ANOVA
results = perform_anova(data)
print(results)
```

## 📁 Project Structure

```
├── anovas/                  # ANOVA analysis implementations
├── clustdimred/            # Clustering and dimensionality reduction
├── confint/                # Confidence intervals
├── correlation/            # Correlation analysis
├── descriptives/           # Descriptive statistics
├── normOutliers/           # Normality tests and outlier detection
├── regressions/            # Regression analysis
├── sigdet/                 # Signal detection
├── ttest/                  # T-test implementations
├── visualization/          # Data visualization tools
├── requirements.txt        # Project dependencies
└── README.md              # Project documentation
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


