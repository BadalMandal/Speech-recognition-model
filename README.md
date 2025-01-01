# 🎤 Speaker Identification System

## 📚 Project Overview
This project implements a **Speaker Identification System** using audio datasets. The system leverages **MFCC (Mel Frequency Cepstral Coefficients)** for feature extraction and **Gaussian Mixture Models (GMM)** for speaker modeling and classification.

---

## 🛠️ Features
- **Audio Preprocessing:** Splits dataset into training and testing datasets.
- **Feature Extraction:** Extracts MFCC features from audio samples.
- **Speaker Modeling:** Implements GMM models for each speaker using `sklearn`.
- **Speaker Identification:** Identifies the speaker from test audio samples.

---

## 📂 Dataset
- The dataset contains multiple audio files corresponding to different speakers.
- DataSet provided with the code

---

## 📦 Dependencies
Ensure the following Python packages are installed:

```bash
pip install numpy scipy sklearn librosa
```

---

## 🚀 How to Run
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/BadalMandal/Speech-recognition-model
   ```

2. **Run the Main Script:**
   ```bash
   python model.ipynb
   ```

3. **Evaluate the System:**
   - Place your test audio files in the appropriate folder.
   - The system will predict and display the identified speaker.

---

## 📊 Workflow
1. **Data Preprocessing:** Load and split the dataset.
2. **Feature Extraction:** Extract MFCC features using `librosa`.
3. **Model Training:** Train a GMM model for each speaker.
4. **Prediction:** Classify test audio samples.

---

## 🧠 Key Concepts
- **MFCC:** Extracts audio signal features that represent the timbral aspects.
- **GMM:** Models speaker characteristics using probabilistic distributions.

---

## 🤝 Contribution
Feel free to open issues or submit pull requests.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments
- Reference: [Feature Extraction using MFCC](https://stackoverflow.com/questions/54160128/feature-extraction-using-mfcc)

---

**Happy Coding! 🎧**
