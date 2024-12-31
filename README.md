# Machine-Learning-Based-Analysis-of-Obesity-Using-NHANES-Data

## Project Overview  
This project leverages machine learning techniques to analyze factors influencing obesity among U.S. adults using data from the **National Health and Nutrition Examination Survey (NHANES)**. The goal is to identify key demographic and socioeconomic factors associated with obesity and to predict weight status categories using regression models.  

The analysis provides insights into obesity prevalence and its correlates, offering a scientific foundation for policymakers to design targeted health interventions.  

---

## Data Source  
**NHANES Dataset:**  
- Publicly available dataset from the U.S. government portal [Data.gov](https://data.gov).  
- Includes detailed demographic and health data for U.S. adults aged 20 years and older.  
- Provides weight status categories: **normal weight**, **overweight**, and **obese**.  

**Potential Limitations:**  
- **Sampling bias:** Underrepresentation of certain groups such as low-income populations.  
- **Time span:** Data covers multiple years but may not reflect recent trends.  
- **Privacy concerns:** Careful interpretation is necessary to avoid stigmatization.  

---

## Project Goals  
1. **Exploratory Analysis:** Understand the distribution of weight status categories among U.S. adults.  
2. **Feature Engineering:** Identify and preprocess demographic and socioeconomic variables affecting obesity.  
3. **Model Development:** Build machine learning models for predicting weight status.  
4. **Model Comparison:** Evaluate and compare the performance of different regression models.  

---

## Machine Learning Models  
1. **Linear Regression:**  
   - Interpretable model for identifying linear relationships between factors and weight status.  

2. **Random Forest:**  
   - Ensemble model for capturing non-linear relationships and interactions among variables.  

3. **Gradient Boosting Regression:**  
   - Advanced model leveraging sequential learning to optimize predictions.  

All models achieved a prediction accuracy of **95% or higher** during evaluation.  

---

## Key Features  
- **Exploratory Data Analysis (EDA):** Visualizations of obesity distribution by age, gender, and socioeconomic status.  
- **Machine Learning Workflow:** Model training, hyperparameter tuning, and performance evaluation.  
- **Interpretability:** Feature importance analysis to identify significant predictors.  
- **Scalability:** Modular design for future data integration and analysis.  

---

## Technical Architecture  
**Languages and Tools:**  
- **Python:** For data preprocessing, model building, and visualization.  
- **Libraries:**  
  - **scikit-learn:** Model training and evaluation.  
  - **pandas/numpy:** Data manipulation and analysis.  
  - **matplotlib/seaborn:** Visualization of trends and results.  

---

## Results  
- Identified **age**, **gender**, **ethnicity**, and **income level** as significant predictors of obesity.  
- Random Forest and Gradient Boosting models outperformed Linear Regression in accuracy and feature interpretability.  
- Generated actionable insights to support targeted interventions for obesity management.  

---

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/YourUsername/ObesityAnalysis.git  
   cd ObesityAnalysis  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. Run the analysis:  
   ```bash  
   python main.py  
   ```  

4. View results: Access the generated visualizations and performance metrics in the `results/` folder.  

---

## Ethical Considerations  
- **Privacy:** Committed to anonymizing data and protecting sensitive information.  
- **Bias Mitigation:** Regular checks for bias to ensure fairness and inclusivity in results.  

---

## Future Improvements  
- Incorporate additional data sources to improve robustness.  
- Experiment with advanced models like neural networks for further performance gains.  
- Extend the analysis to identify regional trends and their implications.  

---

## Authors  
- **Yanzhen Chen**  
  - Contributions: Machine learning model development, data preprocessing, and result interpretation.  

---
