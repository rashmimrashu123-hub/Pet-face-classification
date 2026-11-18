# 🐱🐶 Pet Face Classification Using Python

## 📌 Project Overview

Pet Face Classification is a simple image classification project that identifies whether an input pet image belongs to a **Cat or a Dog**.

This project uses Python and basic image processing techniques to load, preprocess, visualize, and classify pet images. It calculates the average image for each class and compares the input image with both class averages to make a prediction.

## 🎯 Objectives

- To classify pet images into Cat and Dog categories.
- To understand basic image processing using Python.
- To load and preprocess image datasets.
- To visualize images using Matplotlib.
- To calculate model accuracy.
- To predict the class of a new pet image.

## 🛠️ Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical operations and image calculations
- **Matplotlib** – Image visualization
- **Pillow (PIL)** – Image loading and resizing
- **Jupyter Notebook** – Development environment

## 📂 Project Structure

```text
Pet-Face-Classification/
│
├── dataset/
│   ├── train/
│   │   └── cats/
│   │
│   └── test/
│       ├── cats/
│       └── dogs/
│
├── pet.ipynb
│
└── README.md
```

## ⚙️ Project Workflow

1. **Import Libraries:** Import the required Python libraries.
2. **Load Dataset:** Load cat and dog images from the dataset folders.
3. **Image Preprocessing:** Resize images to 128 × 128 pixels and convert them into RGB format.
4. **Normalization:** Normalize pixel values between 0 and 1.
5. **Data Visualization:** Display sample cat and dog images.
6. **Training:** Calculate the average image for the cat and dog classes.
7. **Accuracy Calculation:** Compare the predicted classes with actual labels.
8. **Final Prediction:** Predict whether the input image is a Cat or a Dog.

## 🧠 Classification Method

This project uses a simple average-image comparison method.

- Calculates the average image of cats.
- Calculates the average image of dogs.
- Compares the input image with both average images.
- Calculates the Mean Squared Error (MSE).
- Predicts the class with the lower error.

## 📦 Installation

Install the required libraries:

```bash
pip install numpy matplotlib pillow
```

## ▶️ How to Run the Project

1. Download or clone this repository.
2. Extract the dataset into the project folder.
3. Open the project in Jupyter Notebook.
4. Open `pet.ipynb`.
5. Run all the cells in sequence.
6. View the model accuracy and final prediction.

## 📊 Expected Output

The project displays:

- Sample cat and dog images.
- Number of training and testing images.
- Model accuracy in percentage.
- Final pet prediction.

Example:

```text
================================
       FINAL PET PREDICTION
================================
Image: sample.jpg
Prediction: Dog
================================
```

## 🚀 Future Enhancements

- Improve classification accuracy.
- Use larger and more balanced datasets.
- Implement advanced machine learning algorithms.
- Develop a user-friendly graphical interface.
- Extend classification to more animal categories.

## 👩‍💻 Author

**Rashmi**

Engineering Student | Interested in Python, Machine Learning and Artificial Intelligence.

---

⭐ If you find this project interesting, don't forget to star the repository!
