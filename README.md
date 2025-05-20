# Urban-revenue-prediction-XGBoost
This repository contains my submission for the 2025 DSMLC Final Competition, hosted by the Data Science & Machine Learning Club at the University of Calgary, in partnership with **Urban Systems**, an engineering firm based in Calgary, Alberta.

---
## Objective

To build a predictive machine learning model for estimating urban project revenue using real-world data provided by Urban Systems. The model leverages XGBoost along with feature engineering and hyperparameter tuning to significantly improve prediction accuracy over baseline methods.

---

## Methods Used

- XGBoost Regression
- Log Transformation: to handle skewed revenue distribution
- Feature Engineering 
- Hyperparameter Tuning
- Evaluation Metrics: R², MAE, RMSE
- Visualizations: Residual distribution, Feature importance, Prediction vs Actual

---

## Results

- **R² Score**: 0.99  
- **MAE**: $10,936  
- **RMSE**: $197,227  
- Residuals symmetrically distributed, indicating low bias
- Model performance far exceeded baseline mean-prediction approach

---

## Future Enhancements

- Use Neo4j to extract graph-based features such as relationships between branches, employees and projects.
- Build an interactive dashboard or API for real-time revenue prediction

---

## Contact

- GitHub: [@akabzw24](https://github.com/akabzw24)
- Email: bozhaowang24@gmail.com

---

## Data Disclaimer

- The dataset used in this project was provided by **Urban Systems** exclusively for the **DSMLC Final Competition**.  
- Due to confidentiality agreements, the dataset is **not included** in this repository.
