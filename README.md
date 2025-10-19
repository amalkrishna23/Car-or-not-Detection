🚗 Car vs Non-Car Classifier

A TensorFlow.js web-based deep learning model that classifies images as **Car** or **Not a Car**. Built for fast and efficient inference directly in the browser using a pre-trained model.

## 🧠 Overview

This project allows users to upload an image and instantly determine whether it contains a car. The model runs entirely in the browser — no backend server required!

**Model Architecture:**

* **Base Model:** Custom CNN (or MobileNet-based if applicable)
* **Framework:** TensorFlow.js
* **Output Classes:** Car, Not a Car

## ⚙️ How It Works

1. **Load the Model:**
   The `model.json` and associated `.bin` weight files are loaded using TensorFlow.js.

2. **Preprocess the Image:**
   The uploaded image is resized to 224x224 pixels and normalized for the model.

3. **Predict the Class:**
   The model outputs a probability for the image being a "Car."

4. **Display the Result:**
   The predicted class along with confidence is shown in the browser, along with a visual confidence bar.

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

## 🖼️ Screenshot

*(Optional: Add a screenshot of the app here)*

## 💻 Requirements

* Modern web browser (Chrome, Firefox, Edge)
* TensorFlow.js included via CDN in `index.html`

## ⚡ Features

* Runs entirely in the browser — no backend needed.
* Real-time predictions with confidence visualization.
* Simple, clean user interface.

---

If you want, I can also **add a “Live Demo” section with GitHub Pages instructions** so people can try it online.

Do you want me to add that?
