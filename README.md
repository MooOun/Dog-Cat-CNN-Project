# 🧠 Deep Learning: Dog vs. Cat Image Classifier

This is an end-to-end Deep Learning project that builds a Convolutional Neural Network (CNN) from scratch to classify images of dogs and cats.

This project covers the complete Computer Vision workflow:
1.  **Data Loading:** Using `ImageDataGenerator` to load, rescale, and augment thousands of images from directories.
2.  **Model Building:** Designing and building a CNN architecture using Keras (`Conv2D`, `MaxPooling2D`, `Dense`).
3.  **Model Training:** Training the model on the training set and monitoring `accuracy` and `val_accuracy` per epoch.
4.  **Evaluation:** Plotting the learning curves (Accuracy/Loss) and evaluating the final model's accuracy on the validation set.

## 💻 Tech Stack

* **Python**
* **TensorFlow & Keras:** The core libraries for building and training the Deep Learning model.
* **Matplotlib:** For plotting the training results (learning curves).
* **OS:** For navigating the file directories.

## 📊 Results

The model built from scratch achieved a final accuracy of **[ใส่ Accuracy ของคุณตรงนี้, เช่น: 80.12%]** on the validation set after 15 epochs.

*(Note: The `train/` and `test/` datasets are **not** included in this repository due to their massive size. They can be downloaded from the [Kaggle Dogs vs. Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats).)*