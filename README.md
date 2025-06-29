# 🤚 Hand Gesture Recognition using SVM
This project implements a hand gesture recognition system using the **LEAP GestRecog dataset** and a **Support Vector Machine (SVM)** classifier. The model is trained and tested in **Google Colab**, with the dataset accessed via **Google Drive**.

## 📂 Dataset
- **Name**: LEAP GestRecog
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Structure**: 10 users × 10 gestures × ~200 images per gesture
- **Input Format**: Grayscale `.png` images

## 🧠 ML Model
- **Algorithm**: Support Vector Machine (SVM)
- **Kernel**: Linear
- **Input Size**: 128×128 grayscale images (flattened to 1D)
- **Libraries**: NumPy, OpenCV, scikit-learn, Matplotlib, seaborn

## 🛠️ Steps
1. Mount Google Drive and extract the dataset
2. Preprocess images (grayscale, resize, flatten)
3. Train-test split
4. Train an SVM classifier
5. Evaluate using accuracy, classification report & confusion matrix
6. Visualize predictions

## 📊 Output
- Model accuracy and class-wise performance
- Confusion matrix heatmap
- Visual comparison of predicted vs true labels
