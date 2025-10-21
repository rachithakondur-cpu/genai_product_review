# Gen AI-Powered Product Review Sentiment Analysis

## Overview
This project demonstrates a **mini Gen AI + analytics workflow** for analyzing e-commerce product reviews.  
It combines **Python-based sentiment analysis** with **AI-generated summaries** to automatically extract insights from customer feedback.

---

## 🧩 Features
- Detects **sentiment** (Positive / Negative / Neutral) for product reviews  
- Generates **automated summary insights** using Gen AI (OpenAI GPT)  
- Provides **actionable insights** for product improvement or marketing strategies  
- Works on any CSV dataset of product reviews  

---

## 🛠 Tools & Technologies
- **Python 3**  
- **Pandas** – data manipulation  
- **TextBlob** – quick sentiment analysis  
- **OpenAI GPT** – AI-generated summary (optional)  
- **Google Colab** – cloud notebook environment  



## 📊 Sample Output
| Product | Review_Text | Rating | Sentiment |
|---------|-------------|--------|-----------|
| Headphones | Sound quality is amazing but battery drains fast. | 4 | Positive |
| Smartwatch | Screen lags and the strap broke in a week. | 2 | Negative |

**Gen AI Summary Example:**  
> “Most customers love the sound quality and product performance. Common complaints include battery life and durability issues.”

---

## 🚀 How to Run
1. Open the notebook in **[Google Colab](https://colab.research.google.com/drive/1LlffnYavTrwddd5Ym8u9psla0hVGXEde#scrollTo=D7bHauRJM_RS))**  
2. Install required packages (if not installed):  
```bash
!pip install pandas textblob openai
