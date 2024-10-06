# Heart Disease Prediction

**2022 annual CDC survey data of 400k+ adults related to their health status**

**What subject does the dataset cover?**

According to the CDC, heart disease is a leading cause of death for people of most races in the U.S. (African Americans, American Indians and Alaska Natives, and whites). About half of all Americans (47%) have at least 1 of 3 major risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Other key indicators include diabetes status, obesity (high BMI), not getting enough physical activity, or drinking too much alcohol. Identifying and preventing the factors that have the greatest impact on heart disease is very important in healthcare. In turn, developments in computing allow the application of machine learning methods to detect "patterns" in the data that can predict a patient's condition.

**References:** 

1) https://www.cdc.gov/heart-disease/risk-factors/?CDC_AAref_Val=https://www.cdc.gov/heartdisease/risk_factors.htm
                                                                                                             
                                                                                                               
2) https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data

![Heart Disease Pictures](https://github.com/user-attachments/assets/28523e44-f1ba-45e0-bcd3-905a10917610)



**Distribution of BMI, Age, Gender, General Health, Race with Heart Diesease**


*Distribution of **BMI** with Heart Disease*
![__results___27_0](https://github.com/user-attachments/assets/4cd3c46d-617c-43f4-98f3-bd52c06c8b5a)  
*Distribution of **Age** with Heart Disease*
![__results___28_0](https://github.com/user-attachments/assets/a25bcea6-ad77-4bb8-88a1-eeffac533369)
*Distribution of **Gender** with Heart Disease*
![__results___29_0](https://github.com/user-attachments/assets/818738b3-ae9c-420e-ab54-5f5de817f299)
*Distribution of **General Health** with Heart Disease*
![__results___30_0](https://github.com/user-attachments/assets/fe045efc-5ede-4f59-a6f8-aeeb26e5e427)
*Distribution of **Race** with Heart Disease*
![__results___31_0](https://github.com/user-attachments/assets/02a4c44c-425e-4134-84d2-da2b18f3fd15)


**Ditribution of Other Diseases with Heart Diseases**

![__results___35_0](https://github.com/user-attachments/assets/956ccec8-de3f-4978-b713-b296ff03b50f)


**Ditribution of Smoking over Heart Diseases**

![__results___40_0](https://github.com/user-attachments/assets/16456348-b01a-4e5d-8bac-74c0b750c7c1)

**Heart Disease Prediction Using ML Models**
We will perform 5 types of Machine Learning models on the datasets to check the models performance to the datasets. The 5 models are 

**1) Logistic Regression**

*Logistic Regression Confusion Matrix*
![__results___60_1](https://github.com/user-attachments/assets/9a984e46-291a-4f78-b1ca-cf729a0d1a13)
Logistic Regression Accuracy: 0.7469386801271266

**2) Random Forest**
*Random Forest Confusion Matrix*
![__results___63_1](https://github.com/user-attachments/assets/3de0d815-9696-41eb-9f0f-c86d6dfa3121)
Random Forest Classifier Accuracy: 0.8819405496354459

**3) Gradient Boosting**
"Gradient Boosting Confusion Matrix*
![__results___66_1](https://github.com/user-attachments/assets/5cbbc330-a54b-4788-87c8-38fed9d09a45)
Gradient Boosting Classifier Accuracy: 0.8592260235558048

**4) XG Boost**
*XG Boost Confusion Matrix*
![__results___69_1](https://github.com/user-attachments/assets/bbb1dae6-a54e-4069-98b7-bc8b1181fd00)
XGBoost Classifier Accuracy: 0.9028323051037577

**5) Light GBM**
*Light GBM Confusion Matrix*
![__results___72_1](https://github.com/user-attachments/assets/5f5afc40-2573-4c57-a2a1-405ac48e18be)
LightGBM Classifier Accuracy: 0.9015703869882221


**Conlusion**
We can see that The highest algorithm accuracies is the XGBoost & LightGBM classifier.


*Algorithms	Accuracies*
1 -	Logistic Regression	  0.746939
2	- Random Forest	        0.881941
3	- Gradient Boosting	    0.859226
4	- XGBoost Classifier	  0.902832
5	- LightGBM Classifier	  0.901570

