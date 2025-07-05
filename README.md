# BlightGuard 🥔 - Potato Disease Classification

🚀 A **deep learning pipeline** to classify potato leaf images into **healthy or diseased categories** using Convolutional Neural Networks (CNN). This project helps farmers and researchers detect and monitor potato diseases efficiently to reduce yield loss.

---

## 📌 Features

✅ Classifies potato leaves into:
- Early Blight
- Late Blight
- Healthy

✅ Uses **TensorFlow and Keras CNN** for accurate image classification.

✅ Includes data preprocessing, augmentation, and visualization scripts.

✅ Evaluates model performance with accuracy, loss plots, and confusion matrices.

---

## 🗂️ Project Structure

```
potato-disease-classification/
├── dataset/                # Contains the raw and preprocessed image datasets
├── notebooks/              # Jupyter notebooks for EDA and model experimentation
├── models/                 # Saved trained models
├── utils/                  # Data augmentation and helper scripts
├── train.py                # Training pipeline script
├── predict.py              # Prediction script for single images
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 🛠️ Tech Stack

- **Python 3.x**
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Ganesh-balaji-22/BlightGuard.git
cd potato-disease-classification
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Training

```bash
python train.py
```

### 4️⃣ Make Predictions

```bash
python predict.py --image path_to_image.jpg
```

---

## 📊 Results

✅ Achieved **high classification accuracy** on test data.  
✅ Visualized loss and accuracy plots to monitor overfitting.  
✅ Confusion matrix shows effective separation between healthy and diseased leaves.

---

## 🤝 Contributing

Contributions are welcome!

- Open issues or request features via [GitHub Issues](https://github.com/Ganesh-balaji-22/potato-disease-classification/issues).
- Feel free to fork and submit pull requests.

---

## 📫 Contact

**Ganesh Balaji**  
[LinkedIn](https://www.linkedin.com/in/ganeshbalaji22/)

---

