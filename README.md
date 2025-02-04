## Automated Vehicle Recognition and Parking Control System

## 📌 Problem Definition
Unauthorized vehicle access and inefficient parking allocation on campus create security risks and inconvenience for staff and students, highlighting the need for an automated, optimized parking solution.<br>
<div align ="center">
<img  src = "/anpr_assets/automatic-number-plate-recognition-powered-boom-barrier-500x500.webp" width="500" height="300">
</div>

## 👉 Challenges:<br>

Data Management Issues<br>
Manual Vehicle Monitoring<br>
Unauthorized Access<br>
Inexperienced Personnel
<br>


## 📓 How It Works - Key Techniques Used

1. **Image Preprocessing:**
   Enhancing image quality by adjusting brightness, contrast, and noise reduction for better analysis.  

2. **Number Plate Detection:** 
   Identifying and extracting the vehicle’s number plate region from the image.  

3. **Number Plate Recognition:**  Converting the detected number plate characters into machine-readable text using Optical Character Recognition (OCR).  

4. **Smart Diversion:**
   Automating traffic control by analyzing recognized plates to grant or restrict access based on predefined rules.  


<div align ="center">
Image Processing Techniques:<br><br>

<img src = "/anpr_assets/Picture1.png" width="400" height="200" >
<img src = "/anpr_assets/Picture2.png"  width="400" height="200" >
<img src = "/anpr_assets/Picture3.png"  width="400" height="200" ><br><br>
FILTER CONTOURS AND EXTRACT ROI:<br>

<br>
<img src = "/anpr_assets/Picture4.png"  width="400" height="200">
<img src = "/anpr_assets/Picture5.png" width="400" height="200">
</div>

## 📓 Overview

| Machine Learning Models Applied            | Accuracy |
| ----------------- | ------------------------------------------------------------------ |
| Random Forest | 81.10% |
| Logistic Regression | 80.61% |
| Support Vector Machine | 81.73% |
| XGB_Classifier | 80.52% |
| Gradient Boasting | 82.37% |

<img src = "/assets/Screenshot 2025-02-05 001119.png">

The Dataset was imbalanced so to increase the accuracy I applied SMOTE and then the accuracy of gradient boasting classifier reached `95.12%`.

<img src = "/assets/Screenshot 2025-02-05 001021.png">

<br>

## 👉 Application

The ability to predict churn before it happens allows businesses to take proactive actions to keep existing customers from churning. This could look like: 
```
  Customer success teams reaching out to those high-risk customers to provide support or to gauge 
  what needs may not be being met.
```

The advantage of calculating a company's churn rate is that it provides clarity on how well the business is retaining customers, which is a reflection on the quality of the service the business is providing, as well as its usefulness.

<br>


## 🔗 Dataset:

<a href='https://www.kaggle.com/datasets/blastchar/telco-customer-churn' target="_blank"><img alt='Kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=Kaggle&logoColor=20beff&labelColor=black&color=FFFFFF'/></a>

<br >

## 👉 Conclusion

Conducted in-depth statistical analysis using EDA to identify churn drivers from a dataset of 7,043 customers, focusing on key business metrics like tenure and monthly charges.<br>
Engineered a Gradient Boosting model, achieving 95% accuracy in predicting customer churn and generating actionable insights that improved customer retention.

 
