# Handwritten-Digit-Recognition
# 🖊️ Handwritten Digit Recognition using Deep Learning

A simple AI project that recognizes handwritten digits (0–9) using **Python**, **TensorFlow**, and the **MNIST dataset**. The model is trained on thousands of handwritten digit images and predicts the correct digit from a new input image.

---

## 📌 Features

* Recognizes handwritten digits from **0 to 9**
* Uses the **MNIST** handwritten digit dataset
* Built with **TensorFlow** and **Keras**
* Image preprocessing using **OpenCV**
* High prediction accuracy
* Easy to train and test

---

## 🛠️ Technologies Used

* Python 3.11
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib

---

## 📂 Project Structure

```text
Handwritten-Digit-Recognition/
│
├── train.py              # Model training script
├── predict.py            # Predict handwritten digit
├── model.h5              # Trained model
├── digit.png             # Sample input image
├── requirements.txt      # Required libraries
└── README.md             # Project documentation
```

---

## 📥 Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Handwritten-Digit-Recognition.git
```

2. Open the project folder

```bash
cd Handwritten-Digit-Recognition
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Train the Model

```bash
python train.py
```

### Predict a Digit

Save your handwritten digit image as **digit.png**, then run:

```bash
python predict.py
```

---

## 🧠 How It Works

1. Load the MNIST dataset.
2. Normalize image pixel values.
3. Train a Deep Learning neural network.
4. Save the trained model.
5. Read a handwritten digit image.
6. Predict the digit (0–9).
7. Display the prediction.

---

## 📊 Sample Output

```text
Accuracy: 98.4%

Predicted Digit: 7
```

---

## 📸 Dataset

The project uses the **MNIST Handwritten Digit Dataset**, which contains:

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* Digit classes: 0–9

---

## 🚀 Applications

* Optical Character Recognition (OCR)
* Bank cheque processing
* Postal code recognition
* Automatic form processing
* Educational AI applications
* Document digitization

---

## 🔮 Future Improvements

* Real-time webcam digit recognition
* CNN-based model for improved accuracy
* Handwritten alphabet recognition
* Web application deployment
* Mobile application support

---

## 📄 License

This project is developed for educational and learning purposes.

---

## 👨‍💻 Author

**Subanisharthana S**

BE Computer Science and Engineering (AI & ML)

SSM Institute of Engineering and Technology

Dindigul, Tamil Nadu
