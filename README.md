# 📩 SMS Spam Detection and Ham Classification using Machine Learning & NLP

This project implements a **two-stage NLP-based classification system** that not only detects spam messages but also further categorizes non-spam (ham) messages into **business** or **personal** classes. The pipeline uses robust machine learning techniques like **Random Forest**, **Logistic Regression**, **Multinomial Naive Bayes**, and a **Voting Classifier**, along with TF-IDF features and extensive text preprocessing.

---

## 🚀 Project Highlights

- ✅ **Phase 1:** Spam vs. Ham classification
- ✅ **Phase 2:** Business vs. Personal classification for Ham messages
- ✅ **Datasets Used:**
  - SMS Spam Collection Dataset
  - Custom-labeled Ham (Business/Personal) Dataset
- ✅ **Models Applied:** Logistic Regression, MNB, Decision Tree, Random Forest, Voting Classifier
- ✅ **Text Preprocessing:** Regex cleaning, lemmatization, stopword removal, lowercasing
- ✅ **Feature Extraction:** TF-IDF (max_features=500)
- ✅ **Evaluation Metrics:** Confusion Matrix, F1-Score, ROC Curve, Precision-Recall Curve, Learning Curve
- ✅ **Statistical Testing:** ANOVA for model comparison

---

## 📁 Repository Structure


---

## 📊 Results Summary

| Model                          | Task                     | F1-Score | Accuracy |
|-------------------------------|--------------------------|----------|----------|
| Logistic Regression + TF-IDF  | Spam vs Ham              | 0.96     | 0.96     |
| Multinomial Naive Bayes       | Spam vs Ham              | 0.94     | 0.94     |
| Decision Tree Classifier      | Spam vs Ham              | -        | 0.98     |
| Random Forest Classifier      | Ham (Business/Personal)  | -        | 0.98     |
| Voting Classifier (DT + MNB)  | Spam vs Ham              | 0.99     | 0.98     |

---

## 📷 Sample Visualizations

- 📌 TF-IDF Feature Importance Heatmap
- 📌 Wordclouds for Business vs. Personal messages
- 📌 Confusion Matrices
- 📌 ROC & Precision-Recall Curves
- 📌 Learning Curves for different models

---

## 🧪 How to Run the Project

**Clone the repository**
```bash
git clone https://github.com/sricharanchakravarthula/SMS_CLASSIFICATION
cd SMS_CLASSIFICATION

🛠 Libraries Used
scikit-learn
nltk
pandas
matplotlib
seaborn
wordcloud
scipy (for ANOVA testing)

for further details of the project go throught the paper,code and the report.

👨‍💻 Author
Name: Sricharan Chakravarthula
College: SR University
Contact: sricharan3112004@gmail.com
