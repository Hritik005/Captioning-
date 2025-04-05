This project explores a deep learning-based approach to image captioning aimed at generating natural language 
descriptions of images. The proposed model integrates Convolutional Neural Networks (CNNs) for visual feature extraction
and Recurrent Neural Networks (RNNs) with Long Short-Term
Memory (LSTM) units for language modeling. Key features
include multilingual translation, text-to-speech (TTS), and Braille
encoding, enhancing accessibility for visually impaired users.
The model was trained on the Flickr8k dataset and evaluated
using BLEU metric and human feedback, demonstrating strong
performance on simple images but challenges with complex
scenes

Additional information regarding the model and the objective

# Image Captioning with Braille, Translation & Audio

This project is an end-to-end image captioning system that generates natural language descriptions for images. It also enhances accessibility and multilingual support by:
- Translating captions into **Hindi**
-  Converting captions to **Braille (ASCII representation)**
-  Generating **audio output** using **Text-to-Speech**

---

##  Features

- **Image Captioning** using CNN + LSTM architecture
- **Multilingual Translation** (default: Hindi)
- **Braille Output** for visually impaired users
- **Speech Generation** using Google Text-to-Speech (gTTS)

---

##  Model Architecture

- **Encoder:** Pre-trained `ResNet50` (CNN) extracts image features.
- **Decoder:** `LSTM`-based RNN generates captions word-by-word.
- **Vocabulary Builder:** Tokenizes and filters caption words using SpaCy.

---

##  Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AjayVamsiV/ImageCaptioingBraille.git
   cd ImageCaptioingBraille/Inference
