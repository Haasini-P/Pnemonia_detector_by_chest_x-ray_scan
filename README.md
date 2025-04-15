#  Pneumonia Detection from Chest X-Ray using CNN 

This project presents a deep learning solution for **automated pneumonia detection** using **chest X-ray images**. We leverage a **Convolutional Neural Network (CNN)** for image classification, built using **Python libraries** and deployed with an interactive UI using **Streamlit**.

---

## 🚀 Features

- 🧠 **CNN-based model** trained on chest X-ray images
- 📸 Upload and predict from X-ray scans in real-time
- 📊 Visualization of model confidence
- ⚙️ Built with **Python**, **TensorFlow/Keras**, and **Streamlit**
- 🧪 Tested on standard Pneumonia datasets

---

## 🛠️ Tech Stack

| Layer      | Tools Used             |
|------------|------------------------|
| Frontend   | Streamlit              |
| Backend    | Python, CNN (Keras/TensorFlow) |
| Libraries  | NumPy, OpenCV, Matplotlib, PIL, etc. |
| Dataset    | Kaggle Chest X-ray Dataset / NIH Chest X-ray Dataset |

---

## 🧰 Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/pneumonia-xray-detector.git
cd pneumonia-xray-detector

# 2. Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
```

---

## 🧠 CNN Model Architecture

- Input Layer: 150x150 grayscale images
- 3 Convolutional layers + MaxPooling
- Dropout for regularization
- Fully connected Dense layers
- Output Layer: Sigmoid activation for binary classification (Normal / Pneumonia)

---

## 🖼️ Sample Prediction UI

The Streamlit UI allows you to:
- Upload an X-ray image
- View model's prediction with confidence
- Get real-time feedback instantly

---

## 📊 Dataset Information

We used:
- **Chest X-Ray Images (Pneumonia)** dataset from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- 5,863 X-ray images labeled as `NORMAL` and `PNEUMONIA`

---

## ⚠️ Disclaimer

This model is a **proof-of-concept** and **should not** be used for real medical diagnosis. Consult medical professionals for any health concerns.

---

## 👩‍💻 Contributors

- P.Haasini
- Rohith
- Nishanth
- Syam
- Built for academic and research purposes

---

## 📄 License

This project is licensed under the MIT License.

---
