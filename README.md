# Instagram Fake Account Detector

A machine learning project that classifies Instagram accounts as **fake** or **genuine** based on profile-related features such as username structure, profile picture, followers, and more. Built using Python, this project demonstrates end-to-end data analysis, feature engineering, and model development.

---

## 📌 Project Highlights

- Exploratory Data Analysis (EDA) with visualizations
- Supervised ML model using Decision Tree Classifier
- Feature importance analysis
- Final prediction demo on new user data
- ~94% accuracy on test dataset

---

## 📁 Dataset

The dataset contains Instagram user data collected between March 15–19, 2019, and labeled as fake (1) or genuine (0).

- `train.csv` — Training dataset with 576 records  
- `test.csv` — Testing dataset with 120 records  


---

## ⚙️ Features Used

- `profile pic`: 1 if profile has a picture, else 0  
- `nums/length username`: ratio of numbers in username  
- `fullname words`: count of words in full name  
- `description length`: length of bio  
- `external URL`: 1 if URL is present, else 0  
- `private`: 1 if profile is private, else 0  
- `#posts`, `#followers`, `#follows`





