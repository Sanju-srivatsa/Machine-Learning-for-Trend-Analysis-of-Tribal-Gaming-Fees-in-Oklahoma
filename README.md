# Machine Learning for Trend Analysis of Tribal Gaming Fees in Oklahoma

---

## Project Overview

This project analyzes the historical trends and forecasts future revenues of tribal gaming exclusivity fees in Oklahoma using advanced machine learning techniques. The primary goal is to provide insights that can assist policymakers and tribal officials in strategic planning and resource allocation.

## Data

### Sources
- **Data Source:** The dataset used in this analysis contains monthly records of tribal gaming exclusivity fees from 2006 to the present. It was sourced from publicly available records maintained by the State of Oklahoma.

### Files
- `data/cleaned_file.csv`: Cleaned version of the dataset used for final analysis.
- `data/data-tribal-gaming-exclusivity-fees-2006-present.csv`: Raw data collected from public records.
- `data/feature_engineered_data.csv`: Dataset after applying feature engineering techniques.

## Notebooks

### Analysis and Modeling
- `notebooks/Trend Analysis and Forecasting of Tribal Gaming Exclusivity Fees in Oklahoma.ipynb`: This Jupyter notebook contains the entire process of data cleaning, exploratory data analysis (EDA), feature engineering, and the application of machine learning models. Models used include:
  - **Support Vector Regression (SVR)**
  - **Random Forest Regression**
  - **Gradient Boosting Regression**

  The notebook also includes model evaluation and selection based on performance metrics such as Root Mean Square Error (RMSE) and R-squared.

## Reports

### Documentation
- `reports/Trend Analysis and Forecasting Report.docx`: A comprehensive report documenting the project, including the methodology, results, discussion, and recommendations for future work.
- `reports/Trend Analysis and Forecasting of Tribal Gaming Exclusivity Fees in Oklahoma.html`: An HTML version of the report for easy web viewing.

## Presentation
- `presentation/Trend Analysis and Forecasting Project Presentation.pptx`: A presentation summarizing the project’s key findings and insights. It includes visualizations and a discussion of the most effective models used for forecasting.

## Insights and Learnings

### Key Insights
1. **Seasonal Patterns:** The analysis revealed clear seasonal patterns in the collection of tribal gaming exclusivity fees, with peaks typically occurring mid-year. Understanding these patterns can help in more accurate budget forecasting.
2. **Impact of Economic Events:** Significant economic events, such as the 2008/2009 recession and the COVID-19 pandemic, had noticeable effects on the revenue collected, highlighting the sensitivity of tribal gaming revenues to broader economic conditions.
3. **Model Performance:** Among the machine learning models tested, Gradient Boosting Regression outperformed both Support Vector Regression and Random Forest Regression. It provided the most accurate forecasts, with the lowest RMSE and the highest R-squared, capturing a substantial proportion of the variance in the data.

### What We Learned
- **Importance of Feature Engineering:** Preprocessing steps such as normalization and log transformation significantly improved the performance of the predictive models, demonstrating the critical role of feature engineering in time-series analysis.
- **Model Selection:** The process of comparing different models highlighted the importance of selecting the right model based on the specific characteristics of the dataset. Gradient Boosting Regression was particularly effective due to its ability to handle non-linear relationships and iteratively improve predictions.
- **Data-Driven Decision Making:** The project underscored the value of data-driven approaches in informing policy and strategic planning. By leveraging machine learning, we were able to provide actionable insights that can help stakeholders anticipate future revenue trends and allocate resources more effectively.

## How to Use

### Prerequisites
To run the notebook and replicate the analysis, you need to have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

### Running the Notebook
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/YourUsername/Trend-Analysis-and-Forecasting.git
   ```
2. Navigate to the `notebooks` directory and open the Jupyter notebook:
   ```bash
   cd Trend-Analysis-and-Forecasting/notebooks
   jupyter notebook "Trend Analysis and Forecasting of Tribal Gaming Exclusivity Fees in Oklahoma.ipynb"
   ```
3. Execute the cells in the notebook to run the analysis.

## Project Structure

```
/Trend-Analysis-and-Forecasting/
│
├── README.md
├── data/
│   ├── cleaned_file.csv
│   ├── data-tribal-gaming-exclusivity-fees-2006-present.csv
│   ├── feature_engineered_data.csv
├── notebooks/
│   ├── Trend Analysis and Forecasting of Tribal Gaming Exclusivity Fees in Oklahoma.ipynb
├── reports/
│   ├── Trend Analysis and Forecasting Report.docx
│   ├── Trend Analysis and Forecasting of Tribal Gaming Exclusivity Fees in Oklahoma.html
├── presentation/
│   ├── Trend Analysis and Forecasting Project Presentation.pptx
```

## Conclusion

This project provides a robust framework for analyzing and forecasting trends in tribal gaming fees, utilizing machine learning models to offer predictive insights. The results can be a valuable resource for decision-making in Oklahoma's gaming industry.

---
