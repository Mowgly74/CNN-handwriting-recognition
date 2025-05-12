# 🧠 Handwritten Digit Recognition using CNN

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. The model achieves high accuracy and is capable of predicting digits from image files or screen captures.

## 📌 Features

- Trained on the MNIST dataset
- High accuracy CNN model
- Predict digit from:
  - Uploaded image path
  - Screen capture (e.g., drawn with Paint or GIMP)
- Easy-to-use script with clear output

## 🛠️ Technologies Used

- Python 3
- TensorFlow / Keras
- OpenCV
- NumPy
- PyAutoGUI (for screen capture)
- PIL (Python Imaging Library)

## 📦 Requirements

Before running, make sure to install the following:

```bash
pip install tensorflow opencv-python numpy Pillow pyautogui

> ⚠️ On Linux, screen capture tools like `pyautogui` require GUI access. You must be running in a graphical session (not SSH or headless terminal).

## 🚀 Usage

### 1. Predict from an image path

```bash
python3 Handwritten_Digit_Recognition_CNN.ipynb

⚙️ Installation
Make sure you have Python 3.8+ installed. Then install the required packages:
pip install tensorflow opencv-python numpy Pillow pyautogui

🚀 Usage
Run the notebook or script (.ipynb/.py) and choose input method:

1. Predict from an image file

python3 Handwritten_Digit_Recognition_CNN.py

Then enter:

Choose input mode:
1 - Predict from image path
2 - Predict from screen (after 10 seconds)
Enter choice (1 or 2): 1
Enter full image path: /home/user/digit.png

Choose input mode:
1 - Predict from image path
2 - Predict from screen (after 10 seconds)
Enter choice (1 or 2): 2

You’ll have 10 seconds to draw a digit using Paint or GIMP. The screen is then captured and processed.

📊 Model Performance
Metric	Value
Accuracy	~98.6%
Dataset	MNIST
Epochs	5
Optimizer	Adam
Loss	Categorical Crossentropy





