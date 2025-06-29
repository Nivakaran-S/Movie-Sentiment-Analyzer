# 🎬 Movie Sentiment Analyzer

A web-based sentiment analysis app built with **Streamlit** and **TensorFlow**, capable of predicting whether a movie review is **positive** or **negative**.

---

## 🚀 Overview

This project uses a neural network trained on the **IMDB Movie Review Dataset** to analyze the sentiment of user-inputted movie reviews.

The model was built using:
- TensorFlow’s `Embedding` layer for learning word representations
- A **Simple RNN** layer for sequential processing
- Dense layers for classification

---

## 🧠 Model Architecture

- **Embedding Layer** – Converts words into dense vectors. *(This is a trainable embedding layer in TensorFlow.)*
- **SimpleRNN Layer** – Processes the sequences and learns temporal patterns.
- **Dense Output Layer** – Classifies the review as Positive or Negative using a sigmoid activation.

---

## 📦 Dataset

- IMDB Movie Reviews Dataset
- Contains 50,000 reviews labeled as either **positive** or **negative**
- Preprocessed into padded sequences of integers (word indices)

---

## 💻 How to Run the App

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/movie-sentiment-analyzer.git
   cd movie-sentiment-analyzer

2. **Install dependencies**:
  ```bash
  pip install -r requirements.txt
  ```

3. **Run the app**:
   ```bash
   streamlit run main.py
   ```

--- 

## 🛠 Requirements
All Python dependencies are listed in requirements.txt. Install them before funning the app.

