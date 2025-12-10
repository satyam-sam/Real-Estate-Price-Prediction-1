# Real Estate Analysis & Prediction Project

A comprehensive machine learning project for analyzing and predicting real estate property prices in Gurgaon. This project includes data cleaning, exploratory data analysis (EDA), feature engineering, and multiple machine learning models.

## Project Overview

This project analyzes real estate data including apartments, houses, and flats to build predictive models for property pricing. It includes:

- **Data Cleaning**: Multiple notebooks for cleaning different property types
- **Exploratory Data Analysis (EDA)**: Univariate, multivariate, and pandas profiling analysis
- **Feature Engineering**: Creating new features for better model performance
- **Feature Selection**: Identifying the most important features
- **Model Selection & Optimization**: Testing and comparing different ML models
- **Outlier Treatment**: Handling outliers in the data
- **Baseline Models**: Building baseline models for comparison
- **Recommender System**: Personalized property recommendations
- **Interactive Dashboard**: Streamlit app for data visualization and analysis

## Dataset

The project uses real estate data with the following main files:
- `gurgaon_properties.csv` - Main property dataset
- `flats.csv` - Apartment/flat data
- `houses.csv` - House data

## Project Structure

```
├── Home.py                              # Main Streamlit app
├── pages/
│   └── 2_Analysis_app.py               # Analysis dashboard
├── Notebooks/
│   ├── data-cleaning-*.ipynb           # Data cleaning for different property types
│   ├── EDA-*.ipynb                     # Exploratory data analysis
│   ├── feature-engineering.ipynb       # Feature engineering
│   ├── Feature-Selection.ipynb         # Feature selection
│   ├── Outlier-Treatment.ipynb         # Outlier handling
│   ├── Missing_Value_Imputation.ipynb  # Missing value imputation
│   ├── Model-Selection.ipynb           # Model selection and comparison
│   ├── Baseline Model.ipynb            # Baseline models
│   └── Recommender_system.ipynb        # Recommendation engine
├── data/
│   ├── Raw datasets (.csv files)
│   └── Processed datasets
├── requirements.txt                     # Python dependencies
└── README.md
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Real-Estate.git
cd Real-Estate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Run the Streamlit App
```bash
streamlit run Home.py
```

This will launch the interactive dashboard where you can:
- Explore property data
- Analyze market trends
- View data visualizations
- Get property recommendations

### Run Jupyter Notebooks
Execute any of the analysis notebooks:
```bash
jupyter notebook data-cleaning-gurgaon-properties.ipynb
```

## Key Features

- **Complete Data Pipeline**: From raw data to trained models
- **Multiple Analysis Perspectives**: Different cleaning approaches for different property types
- **Interactive Visualizations**: Streamlit-based dashboard for exploration
- **Machine Learning Models**: Multiple models for price prediction
- **Data Quality Focus**: Comprehensive cleaning, imputation, and outlier treatment
- **Feature Engineering**: Domain-specific features for real estate prediction

## Technologies Used

- **Python 3.x**
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Plotly** - Visualization
- **Scikit-learn** - Machine learning
- **Streamlit** - Interactive web app
- **Jupyter Notebooks** - Analysis and exploration

## Results

The project produces:
- Cleaned and processed datasets
- Trained ML models for price prediction
- Data insights and visualizations
- Property recommendation system

## Author

Your Name

## License

This project is open source and available under the MIT License.

## Acknowledgments

Real estate dataset sourced from public sources.
