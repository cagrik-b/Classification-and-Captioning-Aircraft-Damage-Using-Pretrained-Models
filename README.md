# Classification-and-Captioning-Aircraft-Damage-Using-Pretrained-Models
An automated aircraft damage detection system combining a Convolutional Neural Network (VGG16) for image classification and a Vision-Language Transformer (BLIP) for multimodal image captioning and summarization.
# ✈️ Aircraft Damage Classification and Captioning Pipeline

A deep learning pipeline designed to automatically detect, classify, and summarize aircraft damage using pre-trained vision and multimodal models.

## 📖 Project Overview
Traditional manual inspection of aircraft is time-consuming and prone to human error. This project automates the inspection process by leveraging Transfer Learning. 
1. **Classification Pipeline:** Utilizes a fine-tuned **VGG16** Convolutional Neural Network to classify images into binary damage categories (e.g., Damaged vs. Intact).
2. **Captioning Pipeline:** Utilizes a custom Transformer-based **BLIP** layer to generate natural language descriptions of the detected assets.

## 📂 Project Structure
```text
aircraft-damage-detection/
│
├── data/                   # Place your dataset here
│   ├── train/
│   ├── valid/
│   └── test/
│
├── models/                 # Saved model weights will appear here
│
├── main.py                 # The core execution script
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
