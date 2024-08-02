# Cat vs Dog Image Classification

## Overview

This project involves classifying images of cats and dogs using Support Vector Machines (SVM) and Principal Component Analysis (PCA) for dimensionality reduction.

## Files and Folders

- **`cat_dog/train/train`**: Folder containing training images of cats and dogs.
- **`cat_dog/test1/test1`**: Folder containing test images.

## Steps

1. **Imports and Setup:**
   - Load necessary libraries and set paths for dataset.

2. **Load Data:**
   - Function to load and preprocess training and test images.
   - Images are resized to 100x100 pixels.

3. **Preprocess Data:**
   - Flatten images and split data into training and test sets.
   - Visualize sample images.

4. **Apply PCA:**
   - Perform PCA to reduce dimensionality of image data.

5. **Hyperparameter Tuning:**
   - Use RandomizedSearchCV to find the best SVM parameters.

6. **Model Evaluation:**
   - Evaluate the model on the validation set.
   - Generate confusion matrix and classification report.

## Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Lamrotibsa/PRODIGY_ML_03.git
   ```

2. **Install Dependencies:**
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn opencv-python
    ```

3. **Run the Analysis:**
    Execute the provided Jupyter Notebook
