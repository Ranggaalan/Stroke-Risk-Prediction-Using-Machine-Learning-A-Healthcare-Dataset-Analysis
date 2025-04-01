# **Stroke Risk Prediction Using Machine Learning: A Healthcare Dataset Analysis**  

📌 **Project Description**  
This project aims to predict stroke occurrences based on patient health attributes using machine learning models. The dataset is sourced from Kaggle’s **Healthcare Stroke Dataset**, which includes demographic, medical, and lifestyle-related features. The primary objective is to build an accurate predictive model for early stroke detection, aiding in preventive healthcare strategies.  
![image](https://github.com/user-attachments/assets/0d7577a8-ff22-4d69-b545-70a3d31c8fb1)


📝 **Dataset**  
**Source**: [Kaggle - Healthcare Stroke Dataset](https://www.kaggle.com/code/rishabh057/healthcare-dataset-stroke-data/input)  
**Size**: 5,110 samples, 12 features  

**Features Overview**:  
- **id** – Unique identifier for each patient  
- **gender** – Male, Female, or Other  
- **age** – Patient's age  
- **hypertension** – 1 if the patient has hypertension, 0 otherwise  
- **heart_disease** – 1 if the patient has heart disease, 0 otherwise  
- **ever_married** – Marital status (Yes/No)  
- **work_type** – Type of employment  
- **Residence_type** – Urban or Rural  
- **avg_glucose_level** – Average blood glucose level  
- **bmi** – Body Mass Index  
- **smoking_status** – Smoking history (Never, Former, Smokes)  
- **stroke** – Target variable (1 = Stroke, 0 = No Stroke)  

🔍 **Methodology**  

📌 **Exploratory Data Analysis (EDA)**  
- Distribution analysis of stroke occurrences across age, gender, and medical conditions  
- Feature correlation analysis using heatmaps  
- Outlier detection and handling  
- Data balancing techniques (if necessary)  

📌 **Data Preprocessing**  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling and normalization  
- Splitting dataset into **training (80%)** and **testing (20%)**  

📌 **Machine Learning Models Used**  
✔ **Decision Tree** (Best Model) – **95.56% Accuracy**  
✔ k-Nearest Neighbors (KNN)  
✔ Naïve Bayes  

📌 **Evaluation Metrics**  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-score**  

📊 **Results**  
### EDA
![image](https://github.com/user-attachments/assets/17468a0a-2ab6-41f8-aeef-5e40c1e508c7)

![image](https://github.com/user-attachments/assets/82c9dd86-1669-4cc9-afd5-1b2cf61eee45)

![image](https://github.com/user-attachments/assets/a644e748-34b8-4df2-89af-35508b8c0ea4)

![image](https://github.com/user-attachments/assets/7481205a-8a6e-4641-9a38-651d601ea438)

![image](https://github.com/user-attachments/assets/d1ccc926-d9ba-4466-b5fd-cf60d766ddf7)

![image](https://github.com/user-attachments/assets/940b27ef-0013-4d8b-8af6-a7ae686c466f)

![image](https://github.com/user-attachments/assets/b61d8dbd-afa8-4072-88aa-070f065d4f9c)

### Pemodelan
![image](https://github.com/user-attachments/assets/937a4e8a-dbad-4a2d-933c-76a79f17335f)


📌 **Model Performance Comparison**  
![image](https://github.com/user-attachments/assets/be98ec72-0ed0-4d66-b57b-b7f41925c97f)

| Model | Accuracy |  
|--------|-----------|  
| **Decision Tree** | **95.56%** |  
| KNN | XX.XX% |  
| Naïve Bayes | XX.XX% |  

📌 **Key Visualizations**  
- Feature importance ranking (Decision Tree)  
- Stroke distribution by age, gender, and medical conditions  
- Model performance comparison charts  

💻 **Technologies Used**  
- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: Decision Tree, KNN, Naïve Bayes  
- **Visualization**: EDA plots, heatmaps, classification reports  


🔥 **Conclusion**  
The Decision Tree model achieved the highest accuracy of **95.56%**, making it the best-performing model for stroke prediction. This project provides valuable insights into stroke risk factors and demonstrates the potential of machine learning in preventive healthcare.  
