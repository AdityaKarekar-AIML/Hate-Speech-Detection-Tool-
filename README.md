# 🧠 Hate Speech Detection Tool using NLP and Machine Learning

This is a Python-based desktop application that detects **Hate Speech**, **Offensive Language**, or **Neutral Content** in user-input text using **Natural Language Processing (NLP)** and a **Decision Tree Classifier**. The project features a simple and interactive GUI built with **Tkinter**, making it accessible and easy to use.

---

## 🔧 Features
- Real-time text classification into:
  - Hate Speech Detected
  - Offensive Language Detected
  - No Hate Speech and No Offensive Language Detected
- Text preprocessing using regex and NLTK stopwords
- Vectorization with CountVectorizer
- Trained with Decision Tree Classifier
- GUI interface for easy interaction

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Tkinter, Regex
- **ML Model:** Decision Tree Classifier
- **NLP Tools:** NLTK, CountVectorizer
- **GUI:** Tkinter

---

## 📂 Dataset
- **File:** `twitter_data.csv`
- **Data:** 5,000+ tweets labeled as:
  - `0`: Hate Speech
  - `1`: Offensive Language
  - `2`: Neutral
- Labels are mapped to readable text in the application.

---

## 📈 Text Preprocessing Steps
- Convert text to lowercase
- Remove links, HTML tags, punctuation, numbers
- Remove stopwords using NLTK
- Tokenize and join cleaned text

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detector.git
   cd hate-speech-detector


---

### ✅ Final Steps for GitHub:

1. Create a folder named `assets` in your repo.
2. Add the following images inside it:
   - `Interface.png`
     ![Interface](https://github.com/user-attachments/assets/6c69c285-d86c-4272-9201-1e1c19a0238a)

   - `Hate_speech.png`
     ![Hate speech](https://github.com/user-attachments/assets/741bdf19-1184-4942-8df0-605ae281b304)

   - `Offensive_language.png`
     ![Offensive language](https://github.com/user-attachments/assets/0fbbe655-a2c4-484d-a980-6f5ab14ecd80)

   - `No_hate_speech.png`
     ![No hate speech](https://github.com/user-attachments/assets/1d232870-8833-4ae5-94b4-b7cd59e9133f)

3. Commit the images and `README.md`.
