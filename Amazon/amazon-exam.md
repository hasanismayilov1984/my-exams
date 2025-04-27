# 🛒 Amazon Review Dataset — Full Data Science Exam (Q1–Q20)

---

## 📋 Project Overview

This project transforms a raw Amazon Review dataset into a fully engineered, intelligent, and analysis-ready dataset.

Starting from basic text columns, we applied **advanced lambda operations**, **loops inside lambdas**, **walrus operators `:=`**, and **dynamic scoring mechanisms** to build 20+ brand-new features, clean and ready for machine learning or reporting.

This project simulates real-world end-to-end data preparation and feature engineering — **without shortcuts**, **without copying**, **100% self-coded**.

---

## 🛠 Key Skills Demonstrated

✅ Lambda mastery inside `.apply()`  
✅ Looping inside lambdas  
✅ Walrus operator `:=` usage for clean assignments  
✅ Text cleaning and processing (`lower()`, `split()`, `strip()`)  
✅ Sentiment Analysis (basic + weighted)  
✅ Word classification by length (short, medium, long)  
✅ Word difficulty scoring engine  
✅ DataFrame feature expansion (adding 20+ new columns)  
✅ Visualizations: barplots and pie charts  
✅ GitHub project structuring and publishing

---

## 🧩 Full Features Engineered

| Feature | Description |
|---------|-------------|
| `letter_count` | Total character count in review titles |
| `sentiment_tag` | Simple tag based on word presence |
| `bad` & `great` | Count of "bad" and "great" words separately |
| `word_flag` | Flags inside reviews for bad/great presence |
| `bad_or_good` | Sum of "bad" and "great" word appearances |
| `sentiment_score` | Simple numerical sentiment score |
| `sentiment_label` | Mapped label from sentiment score |
| `splitted` | Exploded review titles into separate words |
| `word_length` | Categorized each word as short, medium, long |
| `average_length` | Average word size per review |
| `total_word_score` | Total points based on word size classification |
| `simple_total_score` | Summed sentiment score (good/bad/terrible) |
| `simple_sentiment_label` | Label based on simple total score |
| `difficulty_score` | Word difficulty score based on lengths |
| `difficulty_label` | Mapped complexity label |

---

## 📝 Final Notes

This project was completed as a full structured exam, solving real-world multi-layer problems without cheating.

Every feature was:

- Thoughtfully designed
- Carefully debugged
- Cleanly coded
- Tested across 1465 Amazon reviews

This is the type of real technical depth companies like Amazon, Google, Meta *should* seek.

💥 **Built by Hasan Ismayilov** — not by tutorials, not by fake CVs —  
but by **pure hard work**, **12 hours per day**, and **love for problem-solving**.

---

# 📂 Repository Structure