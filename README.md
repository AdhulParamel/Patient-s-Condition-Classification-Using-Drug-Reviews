# Patient-s-Condition-Classification-Using-Drug-Reviews

A machine learning-powered Sentiment Analysis Web Application built using **Python**, **Streamlit**, and **Natural Language Processing (NLP)** techniques. The application predicts whether a given text expresses a **Positive**, **Neutral**, or **Negative** sentiment and also identifies the most likely category associated with the input text.

---

## Features

- Predicts sentiment from user input text
- Supports:
  - Positive Sentiment
  - Neutral Sentiment
  - Negative Sentiment
- Displays prediction probabilities
- Interactive web interface using Streamlit
- TF-IDF vectorization for text preprocessing
- Machine Learning classification models for sentiment prediction

---

## Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- NLP (TF-IDF Vectorization)
- Pickle

---

## Project Structure

```bash
├── app.py
├── log_model.pkl
├── tfidf.pkl
├── labeling.pkl
├── lab_model.pkl
├── requirements.txt
└── README.md
```

## How It Works

1. User enters text into the application
2. Text is transformed using TF-IDF Vectorizer
3. Machine Learning models analyze the text
4. The app predicts:
   - Sentiment label
   - Prediction probabilities
   - Most likely associated category

---

## Machine Learning Workflow

- Data Preprocessing
- Text Cleaning
- TF-IDF Feature Extraction
- Model Training
- Sentiment Prediction
- Probability Analysis

---

## Example Output

| Sentiment | Probability |
|------------|-------------|
| Positive | 82.45% |
| Neutral | 12.10% |
| Negative | 5.45% |

---

## Deployment

This application can be deployed using:

- Streamlit Community Cloud
- Render
- Hugging Face Spaces

---

## Future Improvements

- Deep Learning-based sentiment analysis
- Multi-language support
- Emotion detection
- Real-time analytics dashboard
- Improved UI/UX

---



## License

This project is open-source and available under the MIT License.
