# 📰 Fake News Detection Using Machine Learning 🤖👩‍💻

This project implements **fake news detection** using machine learning models to classify news articles as **real** or **fake**. Various machine learning algorithms, including **Logistic Regression**, **Decision Trees**, **Random Forest**, and **Gradient Boosting**, are applied to a labeled dataset of news articles.

---

## 📊 Project Workflow

### 1️⃣ Data Collection 📊
- **Dataset**: Used a labeled dataset of news articles that are categorized as real or fake.
- The dataset contains both **text content** and **labels** indicating whether the news is real or fake.

### 2️⃣ Data Preprocessing 🧹
- **Text Cleaning**: Preprocessing the text data by removing stop words, special characters, and converting text to lowercase.
- **Tokenization**: Split the text into smaller parts (tokens) for easier analysis.
- **Vectorization**: Converted text data into **numerical features** using techniques such as **TF-IDF** (Term Frequency-Inverse Document Frequency) and **Count Vectorizer**.

### 3️⃣ Model Training & Selection 📊
- Split the dataset into **training** and **testing** sets.
- Tried multiple machine learning models:
  - **Logistic Regression**
  - **Decision Trees**
  - **Random Forest**
  - **Gradient Boosting**

### 4️⃣ Evaluation ✅
- **Accuracy**: Evaluated model performance based on accuracy, checking how well the models predicted real and fake news.
- **Classification Reports**: Generated classification reports showing precision, recall, and F1-score for each model.
- **Model Comparison**: Compared the performance of all models to select the best one for fake news detection.

---

## 🛠 Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - **pandas**: For data manipulation and loading datasets
  - **numpy**: For numerical operations
  - **scikit-learn**: For machine learning models and evaluation
  - **nltk**: For text preprocessing and tokenization
  - **matplotlib**: For data visualization (optional for performance graphs)

---

## 📈 Performance

The project includes **several models** to compare which one is the best for detecting fake news. The **accuracy** and **classification report** were used to evaluate each model's performance. 
- **Logistic Regression** and **Random Forest** generally performed well, with **Random Forest** providing the most consistent results.

---


## 📜 Conclusion

This project demonstrates the power of **machine learning** in real-world applications like **fake news detection**. By training multiple models and comparing their performance, this project helps to tackle the growing issue of misinformation.

---

## 📝 Notes

- All models are evaluated on **accuracy**, **precision**, **recall**, and **F1-score**.
