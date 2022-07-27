# HeartDiseaseClassification

# Introduction

As per the Centers for Disease Control and Prevention, one person dies every 36 seconds in the US from heart disease. The Heart is the most important part of our bodies. Any dysfunctionality in the heart will affect other organs of the body. Heart disease has increasingly become one of the leading causes of death in the world. For that, we have decided as a team to create a prediction method for classification of heart disease. A dataset on this subject was extracted from UCI Machine Learning Repository which contains 14 attributes and explained in detail in the coming sections. The creators for this data were:
● Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
● University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
● University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
● V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano,
M.D., Ph.D.

# Problem Definition
Generally medical decisions are often made based on the doctor’s intuition and experience. However, with the current available data, we can generate rich information by applying data mining technique which would help significantly in avoiding the biases and minimizing the decision error. The questions for which we were trying to find answers through data analytics are as follows:
1. What are the key parameters that play a major role in indicating that an individual has a heart disease?
2. What are the effects of outliers on our analysis?
3. How can we know that our chosen model is working efficiently?
4. What is our main class?

# Data Source and Description
This dataset was extracted from UCI Machine Learning Repository. It contains a record of 918 patients, mostly above the age of 30. It looks at 11 attributes which are explained as follow and has 1 target variable column:

1.	Age  - age in years
2.	Sex - (1 = male; 0 = female)
3.	Chest Pain Type
  ●	0: Typical angina: chest pain related decrease blood supply to the heart
  ●	1: Atypical angina: chest pain not related to heart
  ●	2: Non-anginal pain: typically esophageal spasms (non heart related)
  ●	3: Asymptomatic: chest pain not showing signs of disease
4.	RestingBP - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
5.	Cholesterol - serum cholesterol in mg/dl
  ●	serum = LDL + HDL + .2 * triglycerides
  ●	above 200 is cause for concern
6.	FastingBS - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7.	RestingECG - resting electrocardiographic results
  ●	0: Nothing to note
  ●	1: ST-T Wave abnormality
1.	can range from mild symptoms to severe problems
2.	signals non-normal heart beat
  ●	2: Possible or definite left ventricular hypertrophy
1.	Enlarged heart's main pumping chamber
8.	MaxHR - maximum heart rate achieved
9.	Exercise Angina - exercise induced angina (1 = yes; 0 = no)
10.	Oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during exercise unhealthy heart will stress more
11.	ST Slope - the slope of the peak exercise ST segment
  ●	0: Upsloping: better heart rate with exercise (uncommon)
  ●	1: Flat Sloping: minimal change (typical healthy heart)
12.	Heart Disease - have heart disease or not (1=yes, 0=no) 

Dataset URL: https://archive.ics.uci.edu/ml/datasets/heart+disease 

Project by - Manvika Tuteja and Ahmed Alsaadi
