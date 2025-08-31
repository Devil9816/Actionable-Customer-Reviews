# Customer Reviews Sentiment Analysis & Aspect-Level Insights  

## 📖 Project Overview  
This project focuses on analyzing **customer reviews** to uncover valuable insights for businesses.  
It includes:  
- **Sentiment Analysis** (Positive, Negative, Neutral)  
- **Aspect-Level Sentiment Analysis** (sentiment towards product/service features)  
- **Custom Preprocessing Pipeline** with improved stopword handling (negations like *not*, *never* retained)  
- **Baseline Models** using VADER and TextBlob for performance benchmarking  

The future scope of this project includes building an **internal intent classifier** to filter **actionable reviews** (complaints & requests) that can drive maximum ROI for a company.  

---

## 🚀 Key Features  
- **Custom Preprocessing Unit**  
  - Tokenization, lemmatization, stopword removal with preserved negations.  
  - Helps retain critical context in customer feedback.  

- **Sentiment Analysis**  
  - Used **VADER** and **TextBlob** as baseline models.  
  - Comparative analysis of performance across reviews.  

- **Aspect-Level Sentiment Analysis**  
  - Identifies specific product/service aspects customers talk about (e.g., *price, delivery, quality*).  
  - Detects sentiment at **feature level** instead of overall review.  

- **Actionable Review Pipeline (Future Work)**  
  - Building an internal classifier to automatically detect **complaints** and **requests**.  
  - Prioritization of high-ROI reviews for business decisions.  

---

## 📊 Dataset  
- **Source:** Customer reviews dataset (text-based).  
- Preprocessed with custom cleaning steps to handle noise, stopwords, and negations.  

---

## 🛠️ Tech Stack  
- **Languages/Frameworks:** Python, Jupyter Notebook  
- **Libraries:**  
  - NLP: `NLTK`, `spaCy`  
  - Sentiment: `VADER`, `TextBlob`  
  - Data Handling: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  

---

## 📈 Results  
- **Baseline Sentiment Accuracy:**  
  - VADER: ~65%  
  - TextBlob: ~71%  

- **Aspect-Level Insights:**  
  - Extracted sentiments on categories such as *price, delivery, quality, service*.  
  - Provided more fine-grained understanding than overall sentiment.  

---

## 📂 Project Structure

```bash
Actionable-Customer-Reviews/
├── .venv/                        # Virtual environment
│
├── data/                         # Data files
│   ├── Baseline_evals.csv
│   ├── Baseline_predictions.csv
│   ├── cleaned_review.csv
│   ├── finetuned_transformer_evals.csv
│   ├── finetuned_transformer_predictions.csv
│   └── original_dataset.csv
│
├── .gitignore
├── Final_Customer_Reviews.ipynb  # Main notebook with all code
├── readme.md
└── requirements.txt



## 📌 Future Scope  
- Develop **internal complaint/request classifier** for actionable reviews.  
- Deploy as a **Streamlit web app** for interactive business usage.  
- Experiment with **transformer-based models (BERT, DistilBERT)** for better accuracy.  

---

## 👨‍💻 Author  
**Ayush Singh**  
- Data Science & AI Enthusiast  
- Focused on **NLP, Customer Insights, and AI for Business Impact**  
