# 🍷 Wine Quality Prediction — Data Analytics Internship Project

## 📘 Project Overview
This project focuses on **predicting the quality of wine based on its chemical characteristics**, offering a real-world application of **Machine Learning in viticulture**.  
Using advanced data analytics techniques, the model evaluates relationships between chemical attributes such as **acidity, density, sulphates, and alcohol content** to classify wine quality.


## 🎯 Objective
To build and compare multiple **classification models** to predict wine quality effectively and analyze which chemical properties most strongly influence it.


## 🧠 Machine Learning Models Used
1. **Random Forest Classifier**  
2. **Stochastic Gradient Descent (SGD) Classifier**  
3. **Support Vector Classifier (SVC)**


## 🧩 Features in the Dataset
| Feature | Description |
|----------|-------------|
| Fixed Acidity | Tartaric acid level in wine |
| Volatile Acidity | Acetic acid content (vinegar-like taste) |
| Citric Acid | Adds freshness and flavor |
| Residual Sugar | Remaining sugar after fermentation |
| Chlorides | Salt content |
| Free Sulfur Dioxide | Prevents microbial growth |
| Total Sulfur Dioxide | Combined free and bound forms |
| Density | Related to alcohol and sugar content |
| pH | Acidity level |
| Sulphates | Contributes to wine preservation |
| Alcohol | Alcohol percentage |
| Quality | Quality score (target variable) |


## 🧰 Tools and Technologies
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly  
- **Visualization:** Power BI & Jupyter Notebook  
- **Environment:** Jupyter Notebook / Anaconda  
- **Version Control:** Git & GitHub  


## 📊 Data Analysis Workflow

1. **Data Preprocessing**
   - Handled missing values  
   - Created new derived features like sulfur ratio and acidity ratio  
   - Normalized and cleaned dataset  

2. **Exploratory Data Analysis (EDA)**
   - Visualized chemical properties influencing wine quality  
   - Generated correlation heatmaps and pairplots  
   - Compared density, pH, and alcohol across different quality levels  

3. **Model Building**
   - Split dataset into training and testing sets  
   - Trained **Random Forest**, **SGD**, and **SVC** models  
   - Evaluated performance using **classification report**, **accuracy**, and **confusion matrix**

4. **Model Evaluation**
   - Random Forest achieved the best overall accuracy and feature interpretability  
   - Alcohol, sulphates, and volatile acidity showed the strongest correlation with quality  

5. **Visualization**
   - Created professional visuals using **Seaborn, Matplotlib**, and **Plotly**  
   - Designed interactive dashboards using **Power BI**  


## 📈 Key Insights
- Wines with **higher alcohol content and sulphates** tend to receive better quality scores.  
- **Volatile acidity** negatively impacts wine quality.  
- **Random Forest Classifier** outperformed other models in prediction accuracy.

