# 🤖 Amazon Alexa Review Sentiment Analysis

An end-to-end Machine Learning web application built using **Flask**, **XGBoost**, and **Natural Language Processing (NLP)** to analyze customer sentiment from Amazon Alexa reviews. The system supports both single review evaluations in real-time and bulk batch analysis via dataset uploads.

---

## 📌 Features

- **Single Text Sentiment Analysis:** Instantly evaluate individual customer reviews as **Positive** or **Negative**.
- **Bulk Dataset Processing:** Upload `.csv` files containing customer reviews for batch predictions.
- **Automated Visualization:** Generates and embeds interactive pie charts illustrating overall sentiment distributions.
- **CSV Result Export:** Automatically formats and downloads analyzed bulk predictions as a structured `.csv` file.
- **Modern User Interface:** Built with a clean, responsive Tailwind CSS layout.

---

## 🛠️ Tech Stack & Dependencies

- **Backend:** Python 3.x, Flask
- **Machine Learning & NLP:** XGBoost, Scikit-Learn, NLTK, Pandas, NumPy
- **Data Visualization:** Matplotlib / Seaborn
- **Frontend:** HTML5, Tailwind CSS, JavaScript (Alpine.js)

---

## 🚀 Getting Started

Follow these instructions to get a local copy up and running on your machine.

### Prerequisites

Ensure you have Python installed on your system. You can verify by running:
```bash
python --version
```

### Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/anishaacharya0410/Sentiment-Analysis-main.git
   cd Sentiment-Analysis-main
   ```

2. **Run the Application**
   Launch the Flask server:
   ```bash
   python api.py
   ```

3. **Open in Browser**
   Navigate to the local server URL in your web browser:
   ```text
   http://127.0.0.1:5000
   ```

---


## 📊 Dataset Format (For Bulk Upload)

When utilizing the **Bulk CSV Upload** feature, ensure your CSV file includes a text column containing the reviews (e.g., labeled `Sentence` or `verified_reviews`). 

Example format:
| Sentence |
| :--- |
| The sound quality on this Echo Dot is fantastic! |
| Stopped working after two days. Extremely disappointed. |

---
