# Fake-News-Detection-Using-ML-Mini-Project-
Achieved high accuracy by pre-processing and training on labeled datasets.
# 📰 Fake News Detection Using Machine Learning

This mini project demonstrates how to detect **fake news articles** using a machine learning model trained on real-world data. The model uses **Logistic Regression**, **TF-IDF vectorization**, and **NLP techniques** to classify news as either **real** or **fake**.

---

## 📁 Dataset

The dataset contains two CSV files:
- `Fake.csv`: Articles marked as fake news
- `True.csv`: Articles marked as real news

You can download the dataset from this Google Drive folder:

🔗 [Dataset Link (Google Drive)](https://drive.google.com/drive/folders/1I8mb6Tm_3pRgZ3uhdhQHqH4StnlMmSds?usp=drive_link)

---

## 📌 Project Highlights

- ✅ Logistic Regression Model
- ✅ Text Preprocessing using NLTK
- ✅ TF-IDF Vectorization
- ✅ Achieved ~97% accuracy
- ✅ Built and tested using Google Colab

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK (Natural Language Toolkit)
- Google Colab

---

## 📊 Steps Involved

1. **Data Cleaning & Labeling**
   - Combined fake and real news datasets
   - Removed null and noisy data

2. **Text Preprocessing**
   - Lowercasing, punctuation removal
   - Stopwords filtering using NLTK

3. **Vectorization**
   - Used `TfidfVectorizer` to convert text into numerical form

4. **Model Training**
   - Trained using Logistic Regression
   - Evaluated with accuracy score and classification report

---

## 🔍 Example Ou
tput

       0       0.98      0.97      0.97      1782
       1       0.97      0.98      0.97      1820

accuracy                           0.97      3602

---

## 📂 Folder Structure

📦Fake-News-Detection
┣ 📁 data/
┃ ┣ 📄 Fake.csv
┃ ┗ 📄 True.csv
┣ 📄 fake_news_detection.ipynb
┣ 📄 README.md


---

## 🧠 Future Enhancements

- Use advanced NLP models like BERT or LSTM
- Add a web interface with Flask or Streamlit
- Deploy the model using Streamlit Cloud or Heroku

---

## 👨‍💻 Author

Pradip Mali  
📧 pradipmali5474@gmail.com  
📍 India  

---


