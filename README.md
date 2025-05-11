Next Word Prediction Using LSTM and GRU
This repository implements next word prediction using two deep learning models - LSTM and GRU. The models are trained on Shakespeare's "Hamlet" and deployed as web applications using Streamlit.

📂 Project Structure
Next_Word_Prediction_LSTM_GRU/
│── README.md
│── requirements.txt
│── hamlet.txt
│── tokenizer_lstm.pickle
│── tokenizer_gru.pickle
│── next_word_lstm.h5
│── next_word_gru.h5
│── experiments_LSTM.ipynb
│── experiments_GRU.ipynb
│── app_lstm.py
│── app_gru.py
📝 Files and Directories
README.md: Project documentation.

requirements.txt: Python libraries required for the project.

hamlet.txt: Dataset text file containing Shakespeare's 'Hamlet'.

tokenizer_lstm.pickle: Saved tokenizer for LSTM model.

tokenizer_gru.pickle: Saved tokenizer for GRU model.

next_word_lstm.h5: Trained LSTM model.

next_word_gru.h5: Trained GRU model.

experiments_LSTM.ipynb: Jupyter notebook for LSTM model training and evaluation.

experiments_GRU.ipynb: Jupyter notebook for GRU model training and evaluation.

app_lstm.py: Streamlit app for LSTM model.

app_gru.py: Streamlit app for GRU model.

✅ Installation
Clone the repository:

$ git clone https://github.com/your-username/Next_Word_Prediction_LSTM_GRU.git
$ cd Next_Word_Prediction_LSTM_GRU
Create a virtual environment:

$ python -m venv env
$ source env/bin/activate  # Unix/Mac
$ .\env\Scripts\activate  # Windows
Install dependencies:

$ pip install -r requirements.txt
🚀 Running the Jupyter Notebooks
To run the LSTM experiment:

$ jupyter notebook experiments_LSTM.ipynb
To run the GRU experiment:

$ jupyter notebook experiments_GRU.ipynb
🌐 Running the Streamlit Applications
Run the LSTM application:

$ streamlit run app_lstm.py
Run the GRU application:

$ streamlit run app_gru.py
📊 Project Description
