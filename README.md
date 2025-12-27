# Sign Language Recognition System

## 🎯 Project Goal
This project is dedicated to developing a robust system for real-time recognition of American Sign Language (ASL) or a custom set of signs. The goal is to train and evaluate various deep learning models, particularly those based on MobileNetV2, to accurately classify hand gestures into corresponding signs.

## ✨ Features
*   **Deep Learning Models:** Implementation and training of MobileNetV2 for high-accuracy classification.
*   **Model Variants:** Includes several pre-trained model checkpoints (`.h5` files) representing different training phases or accuracy levels.
*   **Development Notebooks:** Jupyter notebooks for data preprocessing, model training, and evaluation.

## 🛠️ Tech Stack
| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Deep Learning** | Keras/TensorFlow | Framework for building and training the neural network models. |
| **Model Architecture** | MobileNetV2 | Efficient convolutional neural network for mobile and embedded vision applications. |
| **Language** | Python | Core programming language. |

## 🚀 Setup and Run Instructions

### Prerequisites
*   Python 3.x

### Installation
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/samermagdy12/sign_language_recognition.git
    cd sign_language_recognition
    ```
2.  **Install dependencies:**
    *(Note: A `requirements.txt` file is highly recommended. You will need to install TensorFlow/Keras and other dependencies manually if one is not present.)*

### Example Usage
1.  **Model Training:** Review and run the notebooks in the `notebooks/` directory (e.g., `sign_Dl.ipynb`) to understand the data preparation and training process.
2.  **Inference:** Load one of the pre-trained models from the `models/` directory (e.g., `mobilenetv2_arsl_final.h5`) to perform real-time sign recognition on new images or video streams.

## 📁 Project Structure
```
sign_language_recognition/
├── models/             # Stores trained model weights and pickles
│   ├── mobilenetv2_arsl_final.h5 # Final trained MobileNetV2 model
│   ├── best_model.h5             # Best model checkpoint
│   ├── rf_model.p                # Random Forest model (if used)
│   └── ...                       # Other model checkpoints
├── notebooks/          # Jupyter notebooks for development and experimentation
│   ├── sign_Dl.ipynb             # Deep Learning model training and evaluation
│   └── ...                       # Other development notebooks
└── README.md           # Project documentation (this file)
```
