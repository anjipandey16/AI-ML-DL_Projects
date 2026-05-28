# Next Word Prediction Using LSTM

This repository features a Deep Learning project focused on Natural Language Processing (NLP) to predict the next word in a given sequence of text. Trained on classic Shakespearean literature, the model utilizes Long Short-Term Memory (LSTM) networks to capture long-term dependencies in text and generate contextually relevant predictions.

---

## 📌 Project Overview

Next Word Prediction (also known as Language Modeling) is a foundational task in NLP, widely used in applications like predictive text keyboards (e.g., Gboard, SwiftKey), smart compose features in emails, and search engine autocompletes.

This project processes a raw text dataset, tokenizes and sequences the text into training samples, and trains a recurrent neural network to predict the most probable next word based on historical context.

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Deep Learning Frameworks:** TensorFlow / Keras
* **Data Manipulation:** NumPy, Pandas
* **Machine Learning Utilities:** Scikit-Learn
* **Development Environment:** Jupyter Notebook (`.ipynb`)

---

## 📁 Repository Structure

```text
Next Word Prediction/
│
├── Shakespare_NextWord_prediction.ipynb   # Main Jupyter notebook containing code & analysis
├── requirements.txt                       # Pre-requisite Python packages
└── README.md                              # Project documentation (this file)

```

---

## ⚙️ Workflow & Architecture

1. **Data Preprocessing:** * Tokenizing the raw Shakespearean text corpus.
* Creating a word-to-index mapping dictionary.
* Generating $N$-gram sequences from the tokenized sentences.


2. **Feature Engineering:**
* Padding sequences to ensure uniform input length.
* Splitting data into input features ($X$) and target labels ($y$).
* Converting target labels into one-hot encoded vectors.


3. **Model Design:**
* **Embedding Layer:** Transforms high-dimensional word vectors into dense semantic representations.
* **LSTM Layer:** Learns sequential patterns and structural dependencies across the text sentences.
* **Dense Output Layer:** Uses a `softmax` activation function to output probability distributions over the entire vocabulary.


4. **Training & Compilation:** * Compiled using `categorical_crossentropy` loss and the `adam` optimizer.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/anjipandey16/AI-ML-DL_Projects.git
cd AI-ML-DL_Projects/Next\ Word\ Prediction

```

### 2. Install Dependencies

Ensure you have Python installed, then install the required libraries:

```bash
pip install -r requirements.txt

```

### 3. Run the Project

Launch Jupyter Notebook to interact with and execute the training pipeline:

```bash
jupyter notebook Shakespare_NextWord_prediction.ipynb

```

---

## 📊 Future Enhancements

* **Bidirectional LSTMs / GRUs:** Experimenting with alternative recurrent architectures to improve contextual accuracy.
* **Transformer Models:** Integrating pre-trained state-of-the-art models like GPT-2 or BERT for superior generation.
* **Deployment:** Wrapping the model in a lightweight web application using Streamlit or Flask for real-time text predictions.
