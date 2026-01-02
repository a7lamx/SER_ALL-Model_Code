
# **Speech Emotion Recognition (SER) Model**

This repository implements a **Speech Emotion Recognition (SER) model** that integrates a **Co-Attention mechanism** to enhance feature fusion across multiple models. The architecture is inspired by the original [transformer-cnn-emotion-recognition](https://github.com/IliaZenkov/transformer-cnn-emotion-recognition) repository by Ilia Zenkov, with significant improvements and extensions.

---

## **📌 Overview**

This repository contains the implementation of a **Speech Emotion Recognition (SER) model** that utilizes advanced deep learning techniques for emotion classification in speech. The key features of this implementation are:

- **Co-Attention Mechanism:** A novel feature fusion technique that combines multiple model outputs for better performance.
- **Multi-Dataset Application:** The model is evaluated on three diverse datasets, namely **ASVP-ESD V1**, **ASVP-ESD V2**, and **ShEmo**.
- **Feature Extraction:** Combines **MFCC** and **Mel spectrograms** to improve emotion recognition accuracy.

🔍 **Inspired by:** [transformer-cnn-emotion-recognition](https://github.com/IliaZenkov/transformer-cnn-emotion-recognition) by Ilia Zenkov.

---

## **📜 Acknowledgements**

This work is largely inspired by the [transformer-cnn-emotion-recognition](https://github.com/IliaZenkov/transformer-cnn-emotion-recognition) repository by **Ilia Zenkov**. We have extended the original architecture with the following contributions:

- **Co-Attention Mechanism:** Added a Co-Attention layer to combine features from multiple models, improving the model’s ability to learn from diverse inputs.
- **Application to Multiple Datasets:** Evaluated the model on three datasets—**ASVP-ESD V1**, **ASVP-ESD V2**, and **ShEmo**—to assess its performance across different conditions and speakers.
- **Improved Accuracy:** Enhanced emotion classification by combining multiple feature extraction techniques, including MFCCs and Mel spectrograms.

---

## **📚 Datasets Used**

This model is evaluated on the following datasets:

1. **[ASVP-ESD V1](https://doi.org/10.5281/zenodo.3782416)**  
   Tientcheu Touko Landry Dejoli, Qianhua He, & Wei Xie. (2020). Audio, Speech and Vision Processing Lab Emotional Sound Database (ASVP-ESD). [DOI: 10.5281/zenodo.3782416](https://doi.org/10.5281/zenodo.3782416)
   
2. **[ASVP-ESD V2](https://doi.org/10.5281/zenodo.7132783)**  
   Tientcheu Touko Landry Dejoli, Qianhua He, & Wei Xie. (2021). Audio, Speech and Vision Processing Lab Emotional Sound Database (ASVP-ESD). [DOI: 10.5281/zenodo.7132783](https://doi.org/10.5281/zenodo.7132783)
   
3. **[ShEMo](https://www.kaggle.com/datasets/mansourehk/shemo-persian-speech-emotion-detection-database)**  
   Mohamad Nezami, Omid and Jamshid Lou, Paria and Karami, Mansoureh. (2019). ShEMO: A large-scale validated database for Persian speech emotion detection. Available on Kaggle: [ShEMo Dataset on Kaggle](https://www.kaggle.com/datasets/mansourehk/shemo-persian-speech-emotion-detection-database)

---


These datasets provide a diverse range of speech samples, including multiple emotions, speakers, and languages, which enables thorough evaluation of the model’s performance.

---

## **🔁 Reproducibility Information**
To enable reproducibility of our experiments, we provide the following details:

Environment:
The code was developed and tested using Python 3.8, with experiments run on a machine using PyTorch 1.13. We recommend using a virtual environment:

bash
Copy
Edit

pip install numpy pandas librosa matplotlib scikit-learn torch torchvision torchaudio


python3 -m venv venv             
source venv/bin/activate         
pip install -r requirements.txt
torch
matplotlib

numpy
pandas
librosa
ipython
webrtcvad

