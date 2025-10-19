# 🚗 Car vs Non-Car Classifier

A TensorFlow.js web-based deep learning model that classifies images as **Car** or **Not a Car**. Built using **MobileNetV2** as the base model for fast and efficient inference directly in the browser.

## 🧠 Overview

This project allows users to upload an image and instantly determine whether it contains a car. The model runs entirely in the browser — no backend server required!

**Model Architecture:**

* **Base Model:** MobileNetV2
* **Framework:** TensorFlow.js
* **Output Classes:** Not a Car, Car

## ⚙️ How It Works

1. **Load the Model:**
   The `model.json` and associated `.bin` weight files are loaded using TensorFlow.js.

2. **Preprocess the Image:**
   The uploaded image is resized to 224x224 pixels and normalized for MobileNetV2 compatibility.

3. **Predict the Class:**
   The model outputs a probability distribution for the two classes: "Car" and "Not a Car."

4. **Display the Result:**
   The predicted class with the highest confidence is displayed to the user, along with a confidence bar.

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/<your-github-username>/Car-vs-Non-Car-Classifier.git
cd Car-vs-Non-Car-Classifier
```

### Run the Project

* Open `index.html` in your browser.
* Ensure all model files (`model.json` and `.bin` files) are in the `model/` folder.
* Upload an image and click **Predict** to see the result.

