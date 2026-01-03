
# RNN Character Predictions ✨

A simple character-level RNN built with TensorFlow/Keras that learns to predict the next character in a repeating text sequence.  
This project demonstrates how recurrent neural networks can capture sequential patterns in text.

---

## 📖 Overview
- Trains on the toy dataset `"hellohellohellohello"`.
- Learns the sequence patterns (`hel → l`, `ell → o`, etc.).
- Predicts the next character given an input sequence.
- Modular, organization-style code with clear functions and docstrings.

---



## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/MarvellousCharacterPredictions.git
cd MarvellousCharacterPredictions
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the project:

```bash
python main.py
```

Expected output:

```
Unique characters: ['e', 'h', 'l', 'o']
Input: ['h', 'e', 'l'] -> Predicted next char: l
```

---

## 📌 Requirements
- Python 3.9+
- TensorFlow 2.x
- NumPy

.

---

## 🚀 Future Enhancements
- Extend to generate longer sequences of text.
- Train on larger datasets (e.g., books, articles).
- Experiment with LSTM/GRU layers for improved performance.
- Add unit tests and CI/CD pipeline.




