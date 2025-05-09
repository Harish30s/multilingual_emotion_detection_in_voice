
# Multilingual Emotion Detection in Voice

This project focuses on detecting emotions from voice recordings across multiple languages using machine learning and signal processing techniques. It aims to enhance human-computer interaction by identifying emotional tone in speech, applicable in customer service, healthcare, and AI assistants.

 📘 Project Overview

The Jupyter Notebook implements a workflow for:
- Preprocessing audio files
- Extracting features (MFCCs, chroma, mel spectrograms)
- Building and training a machine learning model
- Predicting emotional tone from multilingual voice inputs

 🧠 Features

- 🎙️ Multilingual voice emotion detection
- 🧾 Feature extraction using `librosa`
- 🛠️ Emotion classification with machine learning
- 📈 Visualization of dataset and model performance

 🗂️ Project Structure

```plaintext
multilingual_emotion_detection_in_voice.ipynb  # Main notebook
README.md                                      # Project documentation
````

 📦 Requirements

Install required Python packages:

```bash
pip install -r requirements.txt
```

**Key Dependencies:**

* `librosa`
* `numpy`
* `scikit-learn`
* `matplotlib`
* `pandas`
* `soundfile` or `pysoundfile`

 💻 Usage

1. Clone the repository or download the notebook.
2. Prepare your dataset of audio files with labeled emotions.
3. Run the notebook:

   ```bash
   jupyter notebook multilingual_emotion_detection_in_voice.ipynb
   ```
4. Follow the notebook instructions to preprocess data, extract features, train the model, and predict emotions.

 📊 Emotions Supported

Examples (can be modified based on dataset):

* Happy
* Sad
* Angry
* Neutral
* Fear
* Disgust
* Surprise

 🌐 Multilingual Support

* The model is trained/tested on multilingual audio samples.
* Add language-specific preprocessing if required.

 ⚠️ Notes

* Audio files must be in a supported format (e.g., WAV).
* Background noise and low-quality recordings may affect performance.
 📜 License

MIT License

---

 👤 Author

[HARISH S]
