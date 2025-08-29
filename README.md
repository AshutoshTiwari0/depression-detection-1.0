# 🧠 Depression Detection using NLP & Machine Learning  

This project is a **text-based mental health classification app** that uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to detect signs of various mental health conditions from user input.  

The app is powered by **Logistic Regression** and **TF-IDF (Term Frequency–Inverse Document Frequency)** for feature extraction.  

---

## 🚀 Features  
- Classifies text into **7 categories**:  
  - Anxiety  
  - Bipolar  
  - Depression  
  - Normal  
  - Personality Disorder  
  - Stress  
  - Suicidal  
- Built with **Logistic Regression**  
- Uses **TF-IDF** for feature representation  
- Web app deployment support (via `app.py`, `Procfile`, `requirements.txt`, etc.)  

---

## 📊 Model Performance (Key Metrics)  

- **Accuracy**: `0.75`  
- **Weighted F1-score**: `0.74`  
- **Macro F1-score**: `0.71`  

✅ Strong performance in detecting **Normal (0.90 F1)** and **Anxiety/Bipolar (~0.77 F1)**.  
⚠️ Lower performance for **Stress (0.51 F1)** and **Personality Disorder (0.67 F1)**, indicating potential room for improvement with more data.  

---

## 🛠️ Tech Stack  
- **Python**  
- **scikit-learn** (Logistic Regression, TF-IDF)  
- **Streamlit / Flask** (for deployment)  
- **Pickle** (for model persistence)  

---

## 📂 Project Structure  

```bash
├── app.py                       # Main app script  
├── depression_detection.ipynb   # Notebook with model training  
├── model.pickle                 # Trained ML model  
├── tfidf.pickle                 # TF-IDF vectorizer  
├── requirements.txt             # Dependencies  
├── Procfile                     # Deployment config  
├── runtime.txt                  # Python runtime version  
├── setup.sh                     # Setup script for deployment  
├── model_comparison_chart.png   # Model performance visualization 

---
```
## 🚀 Getting Started  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/depression-detection.git

```
2. Move to directory
```bash
cd depression-detection
```
3. Install dependencies
``` bash
pip install -r requirements.txt
```
4. Run the app
``` bash
python app.py
```

For deployment on platforms like Heroku, use the provided Procfile and setup.sh.

📌 Future Improvements

- Improve classification for Stress and Personality Disorder

- Explore deep learning models (LSTMs, Transformers)

- Collect more balanced data for underrepresented classes

⚠️ Disclaimer

This project is for educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.

## 🙏 Acknowledgement  

I would like to thank Abhishek for helping me in deploying the application. Check out his profile here [Kenshi2727](https://github.com/Kenshi2727).
