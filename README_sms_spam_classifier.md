# 📱 SMS Spam Classifier

This is a machine learning project that detects whether an SMS message is **spam** or **ham** (not spam) using natural language processing and classification models.

---

## 🚀 Features

- Data cleaning and preprocessing (lowercasing, removing special characters, etc.)
- Stopword removal using `TfidfVectorizer`
- Feature extraction with TF-IDF
- Classification using:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
- Cross-validation for performance checking
- Model accuracy evaluation

---

## 🗃 Dataset

This project uses the **SMS Spam Collection** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection).  
The dataset contains 5,574 messages labeled as either `ham` or `spam`.

---

## 🛠 How to Use

### 🔧 1. Clone this repository

```bash
git clone https://github.com/your-username/sms-spam-classifier.git
cd sms-spam-classifier
```

### 📦 2. Install dependencies

We recommend using a virtual environment.

```bash
pip install -r requirements.txt
```

Or install the key libraries manually:

```bash
pip install pandas scikit-learn nltk matplotlib
```

### 📓 3. Run the notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open `sms_spam_classifier.ipynb` and run all cells.

---

## 🧪 Sample Results

Cross-validation scores:

```
[0.9757, 0.9784, 0.9766, 0.9757, 0.9748]
Average CV Score: 0.9763
```

---

## 🧠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NLTK
- Matplotlib
- Jupyter Notebook

---

## 📝 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🙌 Acknowledgements

- [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) for the dataset
- Scikit-learn & NLTK for providing awesome NLP tools
