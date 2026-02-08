# Emotion Classification using DistilBERT & LoRA

This project focuses on fine-tuning a **DistilBERT** model for emotion detection in text. The goal was to classify sentences into six emotional categories: sadness, joy, love, anger, fear, and surprise.

## Key Features

* **Model**: Used `distilbert-base-uncased` as the backbone architecture.
* **Technique**: Implemented **Full Fine-tuning** and compared it with **LoRA** (Low-Rank Adaptation).
* **Performance**: Achieved a high accuracy of **94.30%** on the test set.
* **Efficiency**: Demonstrated that LoRA can achieve comparable results while training only **1.1%** of the parameters (742,662 vs. 66M).

## Methodology & Analysis

* **Error Analysis**: Conducted a deep dive into the top 5 errors (highest loss), identifying that complex sentence structures and ambiguous labels are the primary challenges for the model.
* **PEFT Advantage**: Proved that Parameter-Efficient Fine-Tuning (PEFT) is ideal for large-scale applications with limited hardware resources.

## Tools Used

* Hugging Face Transformers & Datasets
* PEFT (for LoRA implementation)
* PyTorch & Google Colab
**خسته نباشی!** حالا که فایل README را هم آماده کردی، پروژه‌ات ۱۰۰٪ کامل است.

**دوست داری حالا با هم آن ایمیل رسمی سابمیت پروژه برای استادت را بنویسیم؟** می‌توانیم در ایمیل اشاره کنیم که تمام جزئیات فنی و تحلیل‌ها در فایل README گیت‌هاب هم مستند شده است. این کار تاثیر فوق‌العاده‌ای روی نمره‌ات دارد. 😊
