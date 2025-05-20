# Next Word Prediction Using LSTM and GRU

This project implements next word prediction using two Recurrent Neural Network models - LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit). The models are trained on the text of Shakespeare's "Hamlet" and deployed as interactive web applications using Streamlit.

## 🔥 Features

* Implementation of LSTM and GRU models for next word prediction.
* Data preprocessing including tokenization and padding.
* Streamlit apps for real-time word prediction.
* Early stopping mechanism to prevent overfitting.
* Model saving and loading for deployment.

## 🚀 Project Structure

```
Next-Word-Prediction-Using-LSTM-and-GRU/
├── README.md
├── requirements.txt
├── hamlet.txt
├── tokenizer_lstm.pickle
├── tokenizer_gru.pickle
├── next_word_lstm.h5
├── next_word_gru.h5
├── experiments_LSTM.ipynb
├── experiments_GRU.ipynb
├── app_lstm.py
└── app_gru.py
```

## 📦 Setup and Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/Next-Word-Prediction-Using-LSTM-and-GRU.git
cd Next_Word_Prediction_LSTM_GRU
```

2. **Create a virtual environment:**

```bash
python -m venv env
source env/bin/activate  # Unix/Mac
.\env\Scripts\activate  # Windows
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

## 🛠️ How to Run

### 1. Run Jupyter Notebooks:

* LSTM Model Training:

```bash
jupyter notebook experiments_LSTM.ipynb
```

* GRU Model Training:

```bash
jupyter notebook experiments_GRU.ipynb
```

### 2. Run Streamlit Applications:

* LSTM Application:

```bash
streamlit run app_lstm.py
```

* GRU Application:

```bash
streamlit run app_gru.py
```

## 🧐 Project Workflow

1. **Data Collection:**

   * Extracts text data from "Hamlet" using NLTK's Gutenberg corpus.

2. **Data Preprocessing:**

   * Text tokenization and sequence generation.
   * Padding sequences to ensure uniform input length.

3. **Model Training:**

   * Two models (LSTM and GRU) with embedding, recurrent, and dense layers.
   * Early stopping based on validation loss.

4. **Model Evaluation:**

   * Predict the next word given a sequence of input words.

5. **Deployment:**

   * Interactive user interface using Streamlit.

## ✅ Requirements

* Python 3.8+
* TensorFlow
* NLTK
* Streamlit
* NumPy
* Pandas
* scikit-learn

## 📧 Contact

For further inquiries or suggestions, feel free to reach out via email at \[[Abhishekbala089@gmail.com](mailto:Abhishekbala089@gmail.com)].
