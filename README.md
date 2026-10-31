# 🧠 Next Word Prediction using LSTM

## 📌 Project Overview

This project is an **AI-powered Next Word Prediction application** built using Long Short-Term Memory (LSTM), a type of Recurrent Neural Network (RNN).

The application predicts the next possible word based on the text entered by the user. It uses deep learning and Natural Language Processing (NLP) techniques to understand sequential text patterns and generate word predictions.

The trained LSTM model is integrated with Streamlit to provide an interactive and user-friendly web interface.

## 🚀 Features

- Predicts the next possible word based on user input.
- Uses LSTM architecture for sequential text learning.
- Converts text into numerical sequences using Tokenizer.
- Applies sequence padding to maintain consistent input length.
- Uses a trained deep learning model for word prediction.
- Interactive web interface built with Streamlit.
- Loads pre-trained model and tokenizer for real-time predictions.

## 🧠 Model Architecture & Workflow

The application follows these steps:

1. **Text Input:** User enters a sentence or a sequence of words.
2. **Tokenization:** Converts input text into numerical sequences using the trained tokenizer.
3. **Sequence Padding:** Adjusts the input sequence to the required length.
4. **LSTM Model:** Processes sequential information and learns contextual patterns.
5. **Prediction:** Generates probability scores for possible next words.
6. **Word Selection:** Uses NumPy's `argmax()` to select the word with the highest predicted probability.
7. **Output:** Displays the predicted next word through the Streamlit interface.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- LSTM (Long Short-Term Memory)
- Natural Language Processing (NLP)
- NumPy
- Pickle
- Streamlit

## 📂 Project Structure

```text
Next-Word-Prediction/
│
├── app.py
├── lstm_model (1).h5
├── tokenizer.pkl
├── max_len.pkl
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd Next-Word-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
python -m streamlit run app.py
```

## 💡 Example

**Input:**
```text
I love machine
```

**Output:**
```text
Predicted Next Word: learning
```

*Note: This is an illustrative example. Actual predictions depend on the trained model.*

## 🎯 Learning Outcomes

Through this project, I explored:

- Understanding LSTM networks and sequential learning.
- Text preprocessing and tokenization.
- Converting text into numerical sequences.
- Applying padding techniques for NLP tasks.
- Training and using deep learning models for next-word prediction.
- Saving and loading trained models using Pickle and Keras.
- Deploying an interactive machine learning application using Streamlit.

## Here is the Live Demo guys go and check just try it!!
link : https://nextwordprediction-jtspnqx3gkmuokr2uvxzse.streamlit.app/


<img width="1366" height="641" alt="Screenshot (530)" src="https://github.com/user-attachments/assets/9f6833e5-ccd1-46c7-bd56-c17ca4b9a06b" />


## Limitations

- The model is trained on a small dataset of approximately 300 sentences.
- Predictions are limited to the vocabulary and patterns learned during training.
- The model may not generate accurate predictions for unfamiliar or complex sentences.
- This project was developed for learning and practicing LSTM-based next-word prediction.

## Future Improvements

- Train the model on a larger and more diverse text dataset.
- Experiment with different LSTM architectures and hyperparameters.
- Improve vocabulary coverage and prediction accuracy.
- Explore advanced language models for better contextual predictions.


## 👩‍💻 Author

**Vibhasha Suthar**

Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast

- GitHub: https://github.com/vibhashasuthar0712
- LinkedIn: https://linkedin.com/in/vibhasha-suthar-280b51351/
