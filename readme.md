# Diabetes Analysis Project

This project contains a Jupyter notebook for analyzing diabetes data using machine learning techniques including classification and regression models.

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd haneentask
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   ```
   
   Activate the virtual environment:
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```
   - **Windows:**
     ```bash
     venv\Scripts\activate
     ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Running the Notebook

Once dependencies are installed, start Jupyter:

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to `diabetes_analysis.ipynb` and run the cells.

Alternatively, if you prefer JupyterLab:
```bash
jupyter lab
```

## Project Contents

- `diabetes_analysis.ipynb` - Main analysis notebook
- `diabetes.csv` - Dataset used for analysis
- `requirements.txt` - Python dependencies
- `readme.md` - This file

## Dependencies

All required Python packages are listed in `requirements.txt` and include:
- pandas - Data manipulation and analysis
- numpy - Numerical computing
- matplotlib - Data visualization
- seaborn - Statistical data visualization
- scikit-learn - Machine learning algorithms
- jupyter - Interactive notebook environment

## Analysis Overview

The notebook includes:
- Exploratory Data Analysis (EDA)
- Data preprocessing and feature engineering
- Classification model (Decision Tree)
- Regression model (Linear Regression)
- Model evaluation and visualization
