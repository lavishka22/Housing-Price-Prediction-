# 🏠 Housing Price Prediction

A comprehensive machine learning project for predicting house prices using multiple regression models. This project includes data cleaning, exploratory data analysis (EDA), advanced visualizations, and comparative model evaluation.

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Models](#models)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Technologies & Dependencies](#technologies--dependencies)
- [Author](#author)
- [License](#license)

## 📖 Overview

This project builds predictive models to estimate house prices based on various property features. By implementing and comparing Linear Regression and Random Forest Regression models, we demonstrate key machine learning workflows including:

- ✅ Data preprocessing and cleaning
- ✅ Exploratory data analysis (EDA) with statistical insights
- ✅ Feature engineering and selection
- ✅ Model training and hyperparameter tuning
- ✅ Performance evaluation with multiple metrics
- ✅ Comprehensive data visualizations

## 📊 Dataset

**File:** `Housing.csv`

The dataset contains housing market data with the following characteristics:

- **Records:** Multiple property listings with various features
- **Target Variable:** Price (continuous numerical value)
- **Features:** Property characteristics including square footage, number of rooms, location, amenities, and other relevant factors
- **Data Preprocessing:** Includes handling of missing values, outlier detection, and feature normalization

### Key Features Used

The model utilizes properties such as:
- Square footage
- Number of bedrooms/bathrooms
- Property age
- Location metrics
- Other relevant real estate attributes

## 🤖 Models

### Linear Regression
- **Purpose:** Establish baseline performance with a simple, interpretable model
- **Strengths:** Fast training, interpretable coefficients, good for understanding feature relationships
- **Use Case:** Baseline comparison

### Random Forest Regression
- **Purpose:** Capture non-linear relationships and feature interactions
- **Strengths:** Handles complex patterns, robust to outliers, feature importance ranking
- **Advantages Over Linear Regression:** Typically achieves better accuracy on real estate data with multiple interacting features

### Performance Metrics
Models are evaluated using:
- **R² Score:** Coefficient of determination (explained variance)
- **Mean Absolute Error (MAE):** Average prediction deviation
- **Root Mean Squared Error (RMSE):** Penalizes larger errors more heavily
- **Mean Squared Error (MSE):** Average squared prediction errors

## 📁 Project Structure

```
Housing-Price-Prediction-/
├── README.md                              # Project documentation
├── LICENSE                                # MIT License
├── Housing.csv                            # Dataset file
├── Housing_Price_Prediction_Summary.docx  # Detailed project report
├── analysis.ipynb                         # Main Jupyter notebook with full analysis
└── charts/                                # Generated visualization outputs
```

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lavishka22/Housing-Price-Prediction-.git
   cd Housing-Price-Prediction-
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

   Or manually install:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

## 💻 Usage

1. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open and run `analysis.ipynb`:**
   - The notebook contains the complete analysis pipeline
   - Run cells sequentially from data loading to model evaluation
   - Visualizations will be generated and displayed inline

3. **Key Notebook Sections:**
   - Data Loading & Exploration
   - Data Cleaning & Preprocessing
   - Exploratory Data Analysis (EDA)
   - Feature Engineering
   - Model Training
   - Model Evaluation & Comparison
   - Visualization & Insights

## 📈 Results

The project delivers:
- ✅ **Model Comparison:** Side-by-side performance metrics for both algorithms
- ✅ **Feature Importance:** Insights into which factors most influence house prices
- ✅ **Visual Analysis:** Distribution plots, correlation heatmaps, and prediction comparisons
- ✅ **Predictions:** Accurate price estimates on test data
- ✅ **Insights:** Key findings about housing market patterns

### Expected Performance
Random Forest typically outperforms Linear Regression on this dataset due to:
- Non-linear relationships in housing prices
- Complex feature interactions
- Better handling of multicollinearity

For detailed results, refer to `analysis.ipynb` and `Housing_Price_Prediction_Summary.docx`.

## 📦 Technologies & Dependencies

| Library | Purpose |
|---------|---------|
| **pandas** | Data manipulation and analysis |
| **numpy** | Numerical computing and arrays |
| **scikit-learn** | Machine learning models and preprocessing |
| **matplotlib** | Data visualization |
| **seaborn** | Statistical visualization |
| **jupyter** | Interactive notebook environment |

### Optional
- **plotly:** Interactive visualizations
- **statsmodels:** Statistical analysis

## 👤 Author

**Lavishka22**

- GitHub: [@lavishka22](https://github.com/lavishka22)
- Repository: [Housing-Price-Prediction-](https://github.com/lavishka22/Housing-Price-Prediction-)

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

The MIT License permits:
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use

With the requirement of:
- 📋 License and copyright notice inclusion

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📞 Support

For questions or issues:
- Open a GitHub Issue
- Check the `analysis.ipynb` for detailed methodology
- Review `Housing_Price_Prediction_Summary.docx` for comprehensive documentation

---

**Last Updated:** June 2026
