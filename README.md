
---

## 📥 Installation & Setup

### ✅ Requirements

- Python 3.8+
- Jupyter or Google Colab
- Libraries:
  - `pandas`
  - `nltk`
  - `scikit-learn`
  - `matplotlib`
  - `wordcloud`

### 💻 How to Run

1. Clone or download the repository.
2. Open the `NLP_Final_Project.ipynb` in **Google Colab** or **Jupyter Notebook**.
3. Unzip the Phishing_Email.csv.zip and cleaned_data.zip. 
4. Run all cells in order:
   - Load and clean the data
   - Preprocess using stemming and stopword removal
   - Train and evaluate the model
   - Use the console input to classify new emails
---- OR -----
1. Open this Colab Link: https://colab.research.google.com/drive/1YrP5jjl2S6MR3DOF8uJjnhu1MeJio4Uu?usp=sharing 
---

## 🚀 Results

- **Model Used:** Multinomial Naive Bayes
- **Accuracy:** 91.77%
- **Classification Report:**
Precision Recall F1-Score
Phishing 0.97 0.82 0.89
Safe Email 0.89 0.98 0.94


## 🧪 Sample Console Output

```python
Enter an email to classify: 
> Your account has been compromised, click this link now!

Classification: Phishing Email


## 📚 References
Dataset Source: Kaggle - Phishing Emails Dataset
https://www.kaggle.com/datasets/subhajournal/phishingemails/data 




## 👨‍💻 Authors
John Patrick Tubigan - Student, [LSPU San Pablo Campus]
Jomarr Jonel Paroan - Student, [LSPU San Pablo Campus]
Janna Tricia Pujeda - - Student, [LSPU San Pablo Campus]


## 📌 License
This project is for educational purposes only and does not come with a license for commercial use.


