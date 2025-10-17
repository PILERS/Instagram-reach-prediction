# Instagram Reach Analysis & Prediction

## 📊 Project Overview

This project builds a machine learning model to predict Instagram post reach based on engagement metrics. By analyzing patterns in impressions, likes, comments, shares, and saves, we can forecast how many unique users a post will reach.

## 🎯 Objective

Predict Instagram post reach using engagement metrics to help content creators and marketers understand what drives post visibility and optimize their content strategy.

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **Scikit-Learn** - Machine learning models and evaluation
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualizations
- **NumPy** - Numerical computing

## 📁 Project Structure
```
instagram-reach-prediction/
│
├── notebooks/
│   └── Instagram_Reach_Model.ipynb    # Main analysis notebook
│
├── data/
│   └── instagram_data.csv             # Sample Instagram metrics dataset
│
├── README.md                          # Project documentation
└── requirements.txt                   # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8 or higher installed on your system.

### Installation

1. Clone this repository:
```bash
git clone https://github.com/PILERS/Instagram-reach-prediction.git
cd Instagram-reach-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `notebooks/Instagram_Reach_Model.ipynb` and run all cells

## 📈 Process & Methodology

### 1. Data Cleaning
- Removed duplicate entries
- Handled missing values
- Filtered out negative values and outliers
- Validated data integrity

### 2. Feature Engineering
Created derived metrics to enhance predictive power:
- **Engagement Rate**: Total engagement / Impressions
- **Like Rate**: Likes / Impressions
- **Comment Rate**: Comments / Impressions
- **Share Rate**: Shares / Impressions
- **Save Rate**: Saves / Impressions
- **Total Engagement**: Sum of all engagement actions
- **Reach Rate**: Reach / Impressions

### 3. Exploratory Data Analysis
- Correlation analysis between variables
- Distribution analysis of reach
- Scatter plots showing relationships between engagement and reach
- Feature importance visualization

### 4. Model Training & Evaluation
Trained and compared two models:
- **Linear Regression**: Baseline model
- **Random Forest**: Ensemble model with better performance

Evaluation metrics:
- R² Score
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## 📊 Key Results

- The Random Forest model achieved strong predictive performance
- **Impressions** and **Total Engagement** are the strongest predictors of reach
- Engagement rates provide additional predictive power beyond raw counts
- Visual comparison of predicted vs actual reach shows model accuracy

## 📉 Visualizations

The notebook includes:
- Correlation heatmaps
- Feature importance charts
- Predicted vs Actual reach scatter plots
- Residual plots for model validation
- Bar charts comparing model performance

## 🔮 Future Improvements

- Incorporate temporal features (time of day, day of week)
- Add content type features (image, video, carousel, reels)
- Test additional models (XGBoost, Neural Networks)
- Hyperparameter tuning for optimization
- Cross-validation for robust performance estimates

## 📝 Dataset

The sample dataset includes 100 Instagram posts with the following metrics:
- Post_ID
- Impressions
- Likes
- Comments
- Shares
- Saves
- Reach (target variable)

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

## 📄 License

This project is open source and available for educational purposes.

## 👤 Author

**Your Name**
- GitHub: [@PILERS](https://github.com/PILERS)

## 🙏 Acknowledgments

- Inspired by real-world Instagram analytics challenges
- Built as a portfolio project for data science learning

