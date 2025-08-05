# Navires 2025 - Small Boat Classification with a CNN

## 📌 Context

This project was developed as part of the Navires 2025 competition hosted on Kaggle by Olivier Ricou.
The goal is to classify small boat images (32x32 pixels) into different categories using a manually built Convolutional Neural Network (CNN) with less than 30 layers.

Reference link for the project skeleton: [Project skeleton - ships25](https://www.lrde.epita.fr/~ricou/iren/skeleton-ships25.html)

## 🧠 Objective
- Build an efficient CNN with fewer than 30 layers.
- Classify the provided dataset of boat images.
- Generate predictions for the test set and submit results to Kaggle.
- Achieve a score better than the organizer’s baseline to pass.

## 🛠️ Methodology
- Load and preprocess the training and test data.
- Define a custom CNN model using TensorFlow / Keras with less than 30 layers
- Compile the model using categorical_crossentropy and the Adam optimizer.
- Train the model with early stopping to prevent overfitting.
- Evaluate the model on a validation set.
- Generate the submission.csv file for final predictions.

## 📈 Results
- Layer count: 29
- Validation accuracy: 0.83166

## 🧪 Dependencies
The project uses the following libraries:
```bash
tensorflow
numpy
pandas
matplotlib
scikit-learn
```

You can install them via:
```bash
pip install -r requirements.txt
```
