# Heart-Attack-Analysis-Prediction-Dataset


## 1. Project Overview

### 1.2. Project Objective
The objective of this project is to develop a data-driven solution to analyze heart attack risk factors, build predictive models for heart attack occurrence, and provide actionable insights for healthcare professionals and patients.

### 1.3. Background
Cardiovascular diseases, particularly heart attacks, are a leading cause of mortality worldwide. Early detection and prevention play a crucial role in reducing the burden of heart disease. Data science and machine learning can be used to analyze medical data to identify risk factors and predict the likelihood of a heart attack in individuals.

### 1.4. Project Timeline
The project is expected to take approximately six to eight months, divided into phases, including data collection and preprocessing, model development, deployment, and post-deployment monitoring.
Resources and Budget
The project will require the expertise of data scientists, machine learning engineers, healthcare professionals, and web developers. Computational resources, access to healthcare data, and necessary software and tools for model development will also be needed.

## 2. Project Scope
The project will encompass the following key components:

**1. Data Collection**: Gather a comprehensive dataset of medical records, including patient demographics, medical history, lifestyle factors, and clinical test results, focusing on patients with and without a history of heart attacks.

**2. Data Preprocessing**: Clean and preprocess the medical data, addressing issues such as missing values, outliers, and data normalization.

**3. Exploratory Data Analysis (EDA)**: Perform a thorough analysis of the data to identify patterns, correlations, and risk factors associated with heart attacks.

**4. Feature Selection**: Determine the most relevant features that significantly contribute to heart attack prediction.

**5. Heart Attack Prediction Models**: Develop machine learning models to predict the likelihood of a heart attack for individual patients. Explore various algorithms such as logistic regression, decision trees, random forests, and neural networks.

**6. Model Evaluation**: Assess model performance using appropriate evaluation metrics (e.g., accuracy, precision, recall, F1-score, ROC-AUC) through cross-validation and other validation techniques.

**7. Interpretability**: Employ model interpretability techniques (e.g., SHAP values or feature importance) to understand the key factors contributing to the prediction.

**8. Patient Risk Assessment**: Create a user-friendly interface for patients and healthcare professionals to input patient information and receive an estimated risk score for a heart attack.

**9. Recommendations and Insights**: Provide actionable insights and recommendations based on the model's predictions to help patients and healthcare providers make informed decisions regarding prevention and intervention.

**10. Deployment**: Deploy the predictive model in a secure and compliant environment, ensuring it meets healthcare data privacy and regulatory standards.

**11. Continuous Improvement**: Establish a mechanism for continuous model improvement through the integration of new data and updates to medical guidelines.

## 3. Project Outcome

### 3.1. Expected Outcomes
1. Heart attack prediction models with high accuracy and interpretability.
2. Identification of critical risk factors and their impact on heart attack occurrence.
3. A user-friendly application for healthcare professionals and patients to assess heart attack risk.
4. Improved early detection and prevention of heart attacks, potentially saving lives.

### 3.2. Project Benefits
1. Early identification of individuals at high risk for heart attacks.
2. Personalized recommendations for patients to reduce their heart attack risk.
3. Enhanced healthcare decision-making and resource allocation.
4. Potential reduction in healthcare costs and improved patient outcomes.

## 4. Figures and Result
### 4.1. Uni-variate Analysis:

![Figure 1 Count of patients age.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%201%20Count%20of%20patients%20age.png)

![Figure 2 Distribution of age.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%202%20Distribution%20of%20age.png)

![Figure 3 Types of chest pain with a number of patients.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%203%20Types%20of%20chest%20pain%20with%20a%20number%20of%20patients.png)

![Figure 4 Distribution of blood pressure around patients.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%204%20Distribution%20of%20blood%20pressure%20around%20patients.png)

![Figure 5 Distribution of cholesterol level around patients.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%205%20Distribution%20of%20cholesterol%20level%20around%20patients.png)

![Figure 6 Distribution of heart rate around patients.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%206%20Distribution%20of%20heart%20rate%20around%20patients.png)

From these charts above, the following conclusions can be drawn:

**1. Age Distribution**: The majority of patients in the dataset fall within the age range of 50 to 60. Among them, the highest number of patients (maximum count) have an age of 56. This suggests that this particular age group may be more prone to the condition or health issue being studied.

**2. Gender Distribution**: Approximately 68.2% (207) of the patients are male, while 31.8% (96) are female. This indicates a higher representation of male patients in the dataset compared to females. It may imply a gender-related difference in the occurrence or diagnosis of the condition under investigation.

**3. Chest Pain Type**: The most common type of chest pain experienced by the patients is categorized as "typical angina" (Value 1 Chest Pain). This finding suggests that this specific type of chest pain is prevalent among the patients in the dataset.

**4. Blood Pressure**: The majority of patients have blood pressure readings falling between 130 and 140. This range may represent the typical blood pressure range for the population being analyzed or indicate a correlation between the condition and blood pressure levels within this range.

**5. Cholesterol Levels**: Most patients in the dataset have cholesterol levels ranging from 200 to 250. This range could be considered normal or expected for the population under study or indicate a potential association between the condition and cholesterol levels within this range.

**6. Heart Rate**: The majority of patients have heart rates ranging from 155 to 165. This range may represent the typical heart rate range for the population being analyzed or suggest a correlation between the condition and heart rates within this range.

### 4.2. Bi-Variate Analysis:

![Figure 7 Does age affect the heart-attack.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%207%20Does%20age%20affect%20the%20heart-attack.png)

![Figure 8 Blood pressure with age.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%208%20Blood%20pressure%20with%20age.png)

![Figure 9 Cholesterol level with age.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%209%20Cholesterol%20level%20with%20age.png)

![Figure 10 Heart rate with age.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%2010%20Heart%20rate%20with%20age.png)

Based on the charts above, the conclusions can be deduced as follows:

**1. Age and Heart Attack**: There is no strong relationship between age and the likelihood of a heart attack. This means that we cannot definitively say that as age increases, the chances of having a heart attack will be higher or lower. Other factors may play a more significant role in determining the risk of a heart attack.

**2. Age and Blood Pressure**: There is a high chance of blood pressure increasing with age. As individuals get older, it is more likely that their blood pressure levels will rise. This suggests that age can be a contributing factor to higher blood pressure readings.

**3. Age and Cholesterol Levels**: There is a high chance of cholesterol levels increasing with age. As individuals age, their cholesterol levels tend to rise. This implies that age can be a factor in the increase of cholesterol levels in the body.

**4. Age and Heart Rate**: There is a high chance of heart rate increasing with age. As individuals get older, their heart rates tend to rise. This indicates that age can influence an increase in heart rate over time.

### 4.3. Multi-Variate Analysis:

![Figure 11 Effect of heart attack with an increase in age and cholesterol.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%2011%20Effect%20of%20heart%20attack%20with%20an%20increase%20in%20age%20and%20cholesterol.png)

![Figure 12 Effect of heart attack with increase in age and blood pressure.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%2012%20Effect%20of%20heart%20attack%20with%20increase%20in%20age%20and%20blood%20pressure.png)

![Figure 13 Effect of heart attack with increase in age and maximum heart rate.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%2013%20Effect%20of%20heart%20attack%20with%20increase%20in%20age%20and%20maximum%20heart%20rate.png)

![Figure 14 Correlation.png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Figure%2014%20Correlation.png)

Based on the charts above, the following conclusions can be derived:
**1. Age and Cholesterol Levels**: There is a correlation between increasing age and increasing cholesterol levels. As individuals get older, their cholesterol levels tend to rise. However, it cannot be definitively concluded that higher cholesterol levels directly cause a higher risk of heart attack. The relationship between cholesterol levels and heart attack risk is complex and may be influenced by other factors.

**2. Blood Pressure and Heart Attack Risk**: There is a clear association between an increase in blood pressure and a higher risk of heart attack. Elevated blood pressure is considered a significant risk factor for heart health, and individuals with high blood pressure are more prone to experiencing heart attacks.

**3. Heart Rate and Heart Attack Risk**: Individuals with a high heart rate have an increased risk of heart attack. A higher heart rate can indicate an increased workload on the heart, potentially leading to cardiovascular complications.

## 5. Modelling
### 5.1. Handle Outliers of the Data
In some Columns there are some Outliers: 
![Handle Outliers of the Data (1).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Handle%20Outliers%20of%20the%20Data%20(1).png)

![Handle Outliers of the Data (2).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Handle%20Outliers%20of%20the%20Data%20(2).png)

As we can see the data set is small. Instead of removing those outliers, we are going to transform them:

![Handle Outliers of the Data (3).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Handle%20Outliers%20of%20the%20Data%20(3).png)

### 5.2. Divide X and y into training and test sets, and use StandardScaler
![Divide X and y into training and test sets, and use StandardScaler (1).png
](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Divide%20X%20and%20y%20into%20training%20and%20test%20sets%2C%20and%20use%20StandardScaler%20(1).png)

### 5.3. Classification Report (KNN):

![Applying K-Nearest Neighbors (KNN) model (1).png
](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Applying%20K-Nearest%20Neighbors%20(KNN)%20model%20(1).png)

### 5.4. Applying K-Nearest Neighbors (KNN) model
![Applying K-Nearest Neighbors (KNN) model (2).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Applying%20K-Nearest%20Neighbors%20(KNN)%20model%20(2).png)

An extensive evaluation of various machine learning models revealed that K-Nearest Neighbors (KNN) emerged as the most effective approach. The subsequent step involves employing KNN for predictive modeling and identifying the optimal value of K, the number of nearest neighbors, that yields the most accurate predictions. This optimization process will enhance the predictive capabilities of the KNN model and ensure reliable forecasting outcomes.

![Applying K-Nearest Neighbors (KNN) model (3).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Applying%20K-Nearest%20Neighbors%20(KNN)%20model%20(3).png)

![Applying K-Nearest Neighbors (KNN) model (4).png](https://github.com/khvu0610/Heart-Attack-Analysis-Prediction-Dataset/blob/0df0b6234cf31fc4dc01d242e0337e88a6554958/Images/Applying%20K-Nearest%20Neighbors%20(KNN)%20model%20(4).png)

A thorough evaluation of the collected data and statistical findings strongly indicates that setting K to 5 yields the most accurate and optimal results. This conclusion is supported by the consistent pattern observed across various metrics, including prediction error, precision, and recall. The choice of K=5 consistently outperformed other values, demonstrating its effectiveness in capturing the underlying relationships within the data. This finding has significant implications for the practical application of the K-Nearest Neighbors algorithm, as it provides a clear guideline for selecting the optimal value of K for achieving superior predictive performance.
## 6. Conclusion
### 6.1. Heart attack prediction models with high accuracy and interpretability.
After evaluating various machine learning algorithms, I opted for K-Nearest Neighbors (KNN) with k=5, as it consistently produced the most accurate predictions for heart disease diagnosis. This outcome highlights the effectiveness of KNN in identifying patterns and relationships within the data, enabling it to make informed predictions about individuals at risk of heart disease.

### 6.2. Identification of critical risk factors and their impact on heart attack occurrence.
While age alone may not directly increase the risk of heart attack, several other factors, such as heart rate, blood pressure, and cholesterol levels, play a significant role.

**Elevated heart rate:** An increased heart rate can put additional strain on the cardiovascular system, making it more susceptible to complications like heart attacks.

**High blood pressure:** Sustained high blood pressure damages the blood vessels and arteries, increasing the risk of plaque buildup and potential blockages that can lead to heart attacks.

**Elevated cholesterol levels:** High cholesterol levels, particularly LDL (low-density lipoprotein), contribute to the formation of plaque in the arteries, narrowing them and increasing the risk of blood clots and heart attacks.

Therefore, maintaining a healthy heart requires addressing not just age but also other modifiable factors like heart rate, blood pressure, and cholesterol levels. Regular check-ups and lifestyle modifications can help manage these risk factors and promote overall heart health.

**The suggestions to avoid heart disease:**
**Maintain a Healthy Weight:** Obesity is a significant risk factor for heart disease, as excessive weight puts undue strain on the heart. Strive to maintain a healthy body mass index (BMI) within the range of 18.5 to 24.9.

**Adopt a Heart-Healthy Diet:** Prioritize a diet rich in nutrient-dense foods, including fruits, vegetables, whole grains, and lean protein sources. Minimize consumption of saturated and trans fats, cholesterol, and sodium.

**Engage in Regular Exercise:** Aim for at least 30 minutes of moderate-intensity exercise most days of the week. Regular physical activity strengthens the heart, enhances blood pressure control, and promotes weight management, all of which contribute to heart health.

**Eliminate Smoking:** Smoking is a leading risk factor for cardiovascular diseases. Cessation of smoking is a crucial step towards improving overall health and reducing the risk of heart disease.

**Effectively Manage Stress:** Chronic stress can elevate blood pressure and heart rate, contributing to heart disease progression. Implement healthy stress management techniques, such as yoga, meditation, or spending time in nature.

**Maintain Control of Blood Pressure, Cholesterol, and Blood Sugar:** Elevated blood pressure, high cholesterol levels, and diabetes are well-established risk factors for heart disease. Collaborate closely with your healthcare provider to manage these conditions effectively.

**Prioritize Regular Check-ups:** Schedule regular consultations with your healthcare provider to monitor your heart health and assess risk factors. Early detection and treatment of heart disease can significantly improve outcomes.

**Additional Recommendations:**
- Moderate alcohol consumption.
- Ensure adequate sleep.
- Cultivate a supportive network to facilitate healthy lifestyle modifications.


### 6.3. User-friendly application for healthcare professionals and patients to assess heart attack risk:**

Develop an intuitive and user-friendly application that can be accessed by both healthcare professionals and patients.
Incorporate a simple interface for inputting relevant data, such as age, gender, medical history, and lifestyle information.
Utilize secure data storage and privacy measures to protect sensitive patient information.
Provide personalized risk assessments and recommendations based on the individual's profile and risk factors.
Present the results in a clear and understandable format, accompanied by actionable steps for prevention and intervention.

### 6.4. Improved early detection and prevention of heart attacks, potentially saving lives:

Implement targeted screening programs to identify individuals at high risk for heart attacks.
Encourage regular health check-ups and screenings to monitor key risk factors and detect warning signs.
Develop educational campaigns to increase awareness about heart attack symptoms, risk factors, and the importance of seeking medical attention promptly.
Promote healthy lifestyle modifications, including proper nutrition, regular exercise, stress management, smoking cessation, and medication adherence.
Collaborate with healthcare providers to ensure timely and appropriate interventions, such as medication management and surgical procedures, for high-risk individuals.
