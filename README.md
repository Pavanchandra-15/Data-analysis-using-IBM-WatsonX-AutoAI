# Data-analysis-using-IBM-WatsonX-AutoAI

Built regression and classification models using **IBM WatsonX AutoAI**.  
This notebook uses city-level air quality data to predict AQI and analyze pollution trends.

---

## 📌 Overview
This project demonstrates how to:
- Clean and preprocess environmental datasets.
- Apply **IBM WatsonX AutoAI** to build optimized regression and classification models.
- Evaluate model performance on both continuous and categorical targets.

---

## 📂 Dataset
**Files included:**
- `city_day_optimized.csv`: Preprocessed air quality dataset with pollutant features and targets (`AQI`, `AQI_Bucket`).
- `Sleep_health_and_lifestyle_dataset.csv`: A health-related dataset (not used in this notebook).

**Source**: Original dataset from city-level air quality records (`city_day.xlsx`), optimized using AutoAI preprocessing pipelines.

---

## ⚙️ Dependencies
- IBM WatsonX AutoAI  
- Python (via WatsonX platform)  
- *(Optional)* Jupyter Notebook or Python environment for exploration

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `city_day_optimized.csv` | Cleaned air pollution dataset for modeling |
| `ML_REPORT (2).pdf` | Detailed report with modeling steps and results |
| `ML Presentation.pptx` | Slide deck summarizing objectives, modeling, outcomes |

---

## 🚀 Workflow

1. **Data Preprocessing**  
   - Handle missing values, feature selection, encoding, and scaling.  
   - Export cleaned data as `city_day_optimized.csv`.

2. **Model Building via WatsonX AutoAI**  
   - Prepare experiments for both regression (`AQI`) and classification (`AQI_Bucket`).  
   - AutoAI automatically performs feature preprocessing, model selection, hyperparameter tuning, and pipeline optimization.

3. **Evaluation**  
   - **Regression**: RMSE, MAE, R²  
   - **Classification**: Accuracy, Precision, Recall, F1-score  
   - Performance summaries included in `ML_REPORT (2).pdf`.

4. **Presentation**  
   - Key highlights, visuals, and conclusions shared in `ML Presentation.pptx`.

---

## 📊 Results Summary

- **Regression (AQI)**: Best RMSE observed → *[1.191]*  
- **Classification (AQI_Bucket)**: Best Accuracy → *[99.8%]*  

> ✨ Add remarks here about **feature importance**, trends, or insights from the dataset.

---

## 🔮 Future Work

- Add meteorological data (temperature, humidity, wind speed) as features.  
- Train city-wise models or apply **time-series forecasting** for AQI.  
- Deploy models as APIs using WatsonX for real-time air quality predictions.

---

## 📬 Contact

If you’d like to collaborate or connect:  
**Email**: pavanchandradevangl@gmail.com  

---
