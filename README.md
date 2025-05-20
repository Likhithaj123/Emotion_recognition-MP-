# Emotion Recognition using EEG Signals

This project focuses on detecting and classifying human emotions using EEG (electroencephalogram) signals and machine learning techniques. The goal is to support mental health monitoring, affective computing, and real-time emotional analysis.

---

## 🧠 Overview

The system reads EEG brainwave signals, extracts frequency band features (using Wavelet Transform or FFT), and classifies emotional states like:
- 😊 Happy
- 😢 Sad
- 😠 Angry
- 😌 Relaxed

In addition to emotion classification, this project includes an **LLM-powered chatbot** to help users understand:
- Which stage of depression they may be in
- Symptoms they might be experiencing
- Personalized precautions and recommendations

---

## 🤖 Chatbot Assistant (LLM Integration)

A key feature of this project is the integration of a **Large Language Model (LLM)** powered chatbot that interacts with users to:

- 📌 Identify the **stage of depression** based on user inputs (e.g., mild, moderate, severe)
- ⚠️ Highlight common **symptoms** related to the detected stage
- 🛡️ Offer personalized **precautions, lifestyle changes**, and **mental health tips**
- 🧘 Suggest activities like meditation, therapy, journaling, music therapy, etc.
- 💬 Provide empathetic and intelligent conversational support

> The chatbot uses emotion classification outputs + user dialogue to tailor its response, acting as a supportive assistant — **not a replacement for medical advice**.

---

## 📁 Dataset

We use publicly available EEG datasets:
- [DREAMER Dataset](https://www.kaggle.com/datasets/)
- [DEAP Dataset](http://www.eecs.qmul.ac.uk/mmv/datasets/deap/)

These include emotion-annotated EEG data with valence, arousal, and dominance values.

---

## ⚙️ Tech Stack

- Python
- NumPy, Pandas, SciPy
- PyWavelets / FFT
- Scikit-learn, TensorFlow, or PyTorch
- React (for chatbot frontend)
- OpenAI API / Hugging Face Transformers (for LLM)
- Matplotlib, Seaborn (visualizations)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Likhithaj123/Emotion_recognition-MP-.git
   cd Emotion_recognition-MP-/emotion_recognization
2. Install dependencies:
   ```bash
     pip install -r requirements.txt

3. Run EEG emotion classifier:
      ```bash
    python train_model.py
4. Start the chatbot:
   ```bash
    npm run chatbot_app.py

📈 Emotion Classifier Results
| Emotion | Accuracy |
| ------- | -------- |
| Happy   | 89.4%    |
| Sad     | 85.2%    |
| Angry   | 83.1%    |
| Relaxed | 87.6%    |


🎯 Future Enhancements
      
- Real-time EEG streaming and classification

- More fine-grained emotional states (e.g., anxious, excited, tired)

- Multilingual chatbot support

-Integration with wearable EEG devices (e.g., Emotiv, Muse)

🙋‍♀️ About Me :-

 Hi! I'm Likhitha, an engineering student passionate about brain-computer interfaces, emotional AI, and mental health innovation. This project blends neuroscience, AI, and empathy to make technology more human-aware.

📬 Contact
    
   GitHub: @Likhithaj123

   Email: [likhithajlikhi@gmail.com]

# Feel free to contribute, fork, or raise issues!
