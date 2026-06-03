# Iris Dataset Analysis

A Jupyter notebook exploration and analysis of the famous Iris flower dataset using Python data science tools.

## Overview

This project provides a comprehensive analysis of the classic Iris dataset, which contains measurements of iris flowers across three different species. The notebook demonstrates fundamental data science workflows including data loading, exploration, statistical analysis, and visualization.

## Dataset

The Iris dataset consists of:
- **150 samples** across 3 iris species
- **4 features** per sample:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- **3 species classes**:
  - Setosa
  - Versicolor
  - Virginica

### Dataset Statistics

| Metric | Sepal Length | Sepal Width | Petal Length | Petal Width |
|--------|--------------|-------------|--------------|-------------|
| Count | 150 | 150 | 150 | 150 |
| Mean | 5.84 cm | 3.06 cm | 3.76 cm | 1.20 cm |
| Std Dev | 0.83 | 0.44 | 1.77 | 0.76 |
| Min | 4.30 cm | 2.00 cm | 1.00 cm | 0.10 cm |
| Max | 7.90 cm | 4.40 cm | 6.90 cm | 2.50 cm |

## Contents

The notebook includes:

1. **Data Loading** - Loading the Iris dataset from scikit-learn
2. **Exploratory Data Analysis (EDA)**
   - Dataset shape and structure
   - First few rows inspection
   - Statistical summaries
   - Data quality checks (missing values)
3. **Visualization**
   - Scatter plots of petal dimensions by species
   - Feature distributions and relationships
4. **Analysis Questions**
   - Average measurements by species
   - Species comparisons
   - Data completeness validation

## Key Findings

- **Virginica** species has the longest sepals on average (6.59 cm)
- **Setosa** species has the shortest sepals on average (5.01 cm)
- **No missing values** in the dataset - all 150 samples are complete
- Clear separation between species based on petal dimensions

## Technologies Used

- **Python 3** - Programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **scikit-learn** - Dataset loading and machine learning utilities

## Requirements

```python
pandas
matplotlib
scikit-learn
```

## Installation

Install the required packages using pip:

```bash
pip install pandas matplotlib scikit-learn
```

## Usage

Open the notebook in Jupyter or Google Colab:

```bash
jupyter notebook Iris_dataset.ipynb
```

Or run directly in [Google Colab](https://colab.research.google.com/).

## Files

- `Iris_dataset.ipynb` - Main analysis notebook

## About the Iris Dataset

The Iris dataset is one of the most famous datasets in machine learning and statistics. It was introduced by Ronald Fisher in 1936 and contains real measurements of iris flowers. It's commonly used for:
- Classification tasks
- Pattern recognition
- Feature analysis
- Educational purposes in data science

## License

This project uses the Iris dataset, which is in the public domain.

## Author

Created by KalonzoBrian

---

**Note**: This repository is ideal for beginners learning data analysis and visualization with Python, as well as for anyone interested in exploring classic machine learning datasets.
