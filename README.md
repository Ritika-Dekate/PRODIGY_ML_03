# PRODIGY_ML_03: SVM for Image Classification (Cats vs. Dogs)

The task involves building a **Support Vector Machine (SVM)** to classify images of cats and dogs using the Kaggle [Dogs vs. Cats dataset](https://www.kaggle.com/c/dogs-vs-cats/data).

---

## **Overview**

The goal of this task is to:
1. Preprocess image data for machine learning.
2. Train an SVM model to classify images into two categories: cats and dogs.
3. Evaluate the model's performance using appropriate metrics.
4. Save the trained model for reuse.

---

## **Features**

- **Image Preprocessing**: 
  - Resized all images to 64x64 pixels.
  - Flattened and normalized pixel values.
  - Balanced the dataset by selecting an equal number of images for both classes.

- **Model Training**:
  - Used an SVM with an RBF kernel, C=1, and gamma='scale'.
  - Split the dataset into 80% training and 20% testing sets.

- **Performance Metrics**:
  - Achieved an accuracy of **64.30%**.
  - Evaluated the model using classification metrics such as precision, recall, and F1-score.

- **Model Persistence**:
  - Saved the trained model using Joblib for reuse.

---

## **Requirements**

Install the following Python libraries:
- `opencv-python`
- `opencv-python-headless`
- `joblib`
- `scikit-learn`
- `numpy`

You can install these libraries using:
```bash
pip install opencv-python opencv-python-headless joblib scikit-learn numpy
