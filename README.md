# 🤖 Sentiment Analysis using Hugging Face

A simple **AI-powered Sentiment Analysis Web Application** built using **Python, Streamlit, Hugging Face Transformers, and PyTorch**.

The application allows users to enter a sentence and uses a pre-trained Hugging Face model to predict whether the sentiment is **Positive** or **Negative**. It also displays the model's confidence score.

---

## 📌 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) technique used to identify the emotional tone of a text.

In this project, a pre-trained **DistilBERT** model from Hugging Face is used to analyze the sentiment of user-provided text.

The application is developed using **Streamlit**, which provides a simple and interactive web interface.

### 🔍 The application predicts:

* 😊 Positive Sentiment
* 😞 Negative Sentiment

---

## 🎯 Objectives

* To understand the basics of Sentiment Analysis.
* To learn how to use Hugging Face Transformers.
* To use a pre-trained NLP model.
* To build an AI application using Streamlit.
* To analyze user-entered text.
* To display sentiment and confidence score.
* To understand how Transformer-based models can be used for NLP tasks.

---

## ✨ Features

* 🤖 AI-based Sentiment Analysis
* 😊 Positive Sentiment Detection
* 😞 Negative Sentiment Detection
* 📊 Confidence Score
* 📝 User Text Input
* 🖥️ Interactive Streamlit Interface
* ⚡ Pre-trained Transformer Model
* 🚀 Real-time Sentiment Prediction

---

## 🛠️ Technologies Used

| Technology                | Usage                              |
| ------------------------- | ---------------------------------- |
| Python                    | Main programming language          |
| Streamlit                 | Web application framework          |
| Hugging Face Transformers | Pre-trained NLP model and pipeline |
| PyTorch                   | Deep learning framework            |
| DistilBERT                | Sentiment analysis model           |

---

## 🧠 Model Used

This project uses the Hugging Face pre-trained model:

```text
distilbert-base-uncased-finetuned-sst-2-english
```

### About the Model

**DistilBERT** is a smaller and faster version of BERT.

The model used in this project is fine-tuned for **binary sentiment classification** using the **SST-2 (Stanford Sentiment Treebank)** dataset.

The model predicts:

```text
POSITIVE
```

or

```text
NEGATIVE
```

It also returns a confidence score for the prediction.

---

## 🔄 How It Works

```text
User enters a sentence
        ↓
Streamlit receives the text
        ↓
Hugging Face Sentiment Analysis Pipeline
        ↓
DistilBERT Model
        ↓
Sentiment Prediction
        ↓
Positive / Negative
        ↓
Confidence Score
        ↓
Result displayed in Streamlit
```

---

## 📂 Project Structure

```text
Sentiment-Analysis/
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 📦 Required Libraries

The project uses the following Python libraries:

```text
streamlit
transformers
torch
```

---

## 📝 requirements.txt

Create a file named:

```text
requirements.txt
```

Add:

```text
streamlit
transformers
torch
```

## 🖥️ How to Use

### Step 1

Run the Streamlit application.

### Step 2

Enter a sentence in the text box:

```text
I really enjoyed this movie!
```

### Step 3

Click:

```text
Analyze Sentiment
```

### Step 4

The application displays the predicted sentiment and confidence score.

---

## 🧪 Example 1 – Positive Sentiment

### Input

```text
I really enjoyed this movie!
```

### Output

```text
😊 Positive Sentiment

Sentiment: POSITIVE
Confidence: 99.XX%
```

---

## 🧪 Example 2 – Negative Sentiment

### Input

```text
I did not like this movie.
```

### Output

```text
😞 Negative Sentiment

Sentiment: NEGATIVE
Confidence: XX.XX%
```

## 🧠 NLP Concept

This project demonstrates a basic **Natural Language Processing (NLP)** application.

NLP allows computers to process and analyze human language.

Sentiment Analysis is commonly used to understand opinions and emotions expressed in text.

### Applications of Sentiment Analysis

* ⭐ Product Reviews
* 🛍️ Customer Feedback
* 📱 Social Media Analysis
* 🎬 Movie Reviews
* 💬 Customer Support
* 📊 Market Research
* 📝 Survey Analysis

---

## 📚 Learning Outcomes

Through this project, I learned:

* Basics of Natural Language Processing
* Sentiment Analysis
* Hugging Face Transformers
* Pre-trained Transformer models
* DistilBERT
* Model inference
* Confidence scores
* Streamlit
* PyTorch
* Building AI-powered web applications using Python

---

## ⚠️ Limitations

* The model is mainly designed for English text.
* The model currently supports Positive and Negative sentiment classification.
* Sarcasm may not always be detected correctly.
* Complex emotions may not always be classified accurately.
* The confidence score represents the model's prediction confidence and is not a guarantee of correctness.

---

## 🚀 Future Enhancements

The project can be improved by adding:

* 😐 Neutral sentiment detection
* 📊 Sentiment charts and graphs
* 📁 CSV file upload
* 📈 Sentiment statistics
* 🔄 Batch sentiment analysis
* 🌍 Multilingual sentiment analysis
* ⭐ Rating prediction
* 💬 Chat-based sentiment analysis
* 🎨 Improved user interface
* ☁️ Online deployment

---

### Technologies

* Streamlit
* Hugging Face Transformers
* PyTorch
* DistilBERT

---

## 📸 Application Screenshot

After running the application, you can take a screenshot of your Streamlit page and add it to the repository.

For example:

```text
![Sentiment Analysis Application](screenshot.png)
```

If you add the screenshot, keep the image file in the same repository:

```text
Sentiment-Analysis/
│
├── app.py
├── requirements.txt
├── README.md
└── screenshot.png
```
