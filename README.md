# Phishing_Website_Detection-FAI
# Phishing Website Detection using Machine Learning

This project aims to develop an efficient machine learning model to detect phishing websites using URL-based features and deploy the model for real-time detection.

## 📌 Project Title
**Phishing Website Detection using Machine Learning**

## 👥 Team Members
- **Varshitha Thilak Kumar** – varshitha.9a2019@gmail.com
- **Siri Sanjana S** – sirisanjana.singareddy@gmail.com
- **Shreya Arun** – shreyaarun005@gmail.com 
- **Anagha Menon** 

**Supervised by:**  
Mr. Sathish, Assistant Professor  
School of Artificial Intelligence, Amrita Vishwa Vidyapeetham

---

## 📖 Abstract

The project focuses on detecting phishing websites by extracting and analyzing 22 key features from URLs. A **Random Forest** model was trained on a dataset of 8,000 phishing and 8,000 legitimate URLs. PCA was applied for dimensionality reduction, improving accuracy and interpretability. The final model is capable of real-time URL classification to enhance cybersecurity measures.

---

## 🎯 Objectives
- Develop an accurate phishing detection model using machine learning.
- Perform feature engineering on URLs.
- Apply dimensionality reduction via PCA.
- Deploy the model for real-time phishing detection.

---

## 🏗️ System Architecture & Workflow

1. **Data Collection**: Gather phishing and legitimate URLs.
2. **Preprocessing**:
   - Label data (`0` = legitimate, `1` = phishing)
   - Clean and format data
3. **Feature Extraction** (22 Features including):
   - URL length
   - Path depth
   - Use of HTTPS
   - Entropy value
   - Special characters, suspicious keywords, etc.
4. **Model Building**:
   - Train a Random Forest classifier
   - Apply PCA for feature reduction
5. **Evaluation**:
   - Accuracy: ~94%
   - Precision, Recall, F1-score, and Confusion Matrix
6. **Deployment**:
   - Model exported using `joblib`
   - Interactive script for real-time predictions

---

## 📊 Results

| Metric     | Score         |
|------------|---------------|
| Accuracy   | 93.6%         |
| Precision  | 94%           |
| Recall     | 92–95%        |
| F1 Score   | 94%           |

- PCA reduced the dataset to **13 significant features**.
- Heatmaps and correlation matrices used for feature importance analysis.

---

## 🚀 Future Work

- Use advanced ML models or deep learning for better performance.
- Expand dataset for better generalization.
- Integrate with browsers for **real-time phishing detection**.
- Include behavioral analysis of user interactions.

---



## 📚 References

1. Jain, A. K., & Gupta, B. B. (2018). *Telecommunication Systems*.
2. Safi, A. & Singh, S. (2023). *Journal of King Saud University*.
3. Kiruthiga & Akila (2019). *IJRTE*.
4. Subasi et al. (2017). *IEEE ICECTA*.
5. Zhuang et al. (2012). *IEEE Distributed Systems Workshops*.

---

## 🛡️ Impact

This machine learning approach to phishing detection demonstrates the real-world potential of AI in combating evolving cybersecurity threats, offering scalable and adaptive protection to internet users worldwide.

