# ML-models-cctv-shoplifting-detection
# Shoplifting & Suspicious Behavior Detection Using Computer Vision with Trained ML Models

A Computer Vision-based security system designed to detect shoplifting and suspicious activities in retail environments in real-time. This project utilizes Deep Learning models to identify specific anomalous behaviors and provide visual bounding box alerts on potential theft actions.

---

## 🌟 Features
* **Real-time Suspicious Behavior Detection:** Classifies actions into "Normal" or "Suspicious" categories.
* **Optimized Object Localization:** Draws clean, minimalist bounding boxes around detected suspicious actions/objects without cluttering the screen.
* **Hardware Acceleration Ready:** Built to support efficient inference using available hardware resources.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Framework Frameworks:** TensorFlow / Keras (or PyTorch, silakan sesuaikan dengan modelmu)
* **Computer Vision:** OpenCV
* **Deployment/Interface:** Streamlit / Flask (Hapus jika tidak pakai GUI)

## 📊 Dataset & Model Architecture
Project ini menggunakan pendekatan Transfer Learning untuk mendeteksi anomali perilaku manusia.
* **Base Model:** MobileNetV2 (Ringan dan cocok untuk deteksi real-time)
* **Input:** Video Stream / Frame CCTV

---

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
Make sure you have Python 3.8+ installed. It is highly recommended to use a virtual environment.

```bash
# Clone this repository
git clone [https://github.com/USERNAME_KAMU/NAMA_REPO_KAMU.git](https://github.com/USERNAME_KAMU/NAMA_REPO_KAMU.git)
cd NAMA_REPO_KAMU

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
