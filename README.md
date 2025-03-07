# Flower Classification with CNN 🌸

## Project Overview

This project demonstrates the use of a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to classify flowers into 5 distinct categories. The model is trained using a flower image dataset and leverages image augmentation techniques to improve performance. Once trained, the model can predict the flower type of any given image.

## 🚀 Key Features

- **CNN Architecture** with Convolutional layers, Pooling layers, and a Fully Connected layer.
- **Image Augmentation** techniques like shear, zoom, and horizontal flipping to enhance dataset variety.
- **5-Class Classification** for flower types: Tulip, Daisy, Rose, Sunflower, and Lily.
- **High Accuracy**: The model achieves a high level of accuracy after 25 epochs of training.

## 🧩 Dataset

- **Training Set**: 2,198 flower images, categorized into 5 classes.
- **Test Set**: 548 images for model evaluation.
- **Directory Structure**:
  - `train_flowers/`: Folder containing training images, organized by class.
  - `test_flowers/`: Folder containing test images, also organized by class.

### Classes
- Tulip
- Daisy
- Rose
- Sunflower
- Lily

## ⚙️ How to Use

1. **Clone the repo**:  
   Clone the repository to your local machine.

2. **Install dependencies**:  
   Install the required libraries.

3. **Train the Model**:  
   Organize the dataset into `train_flowers` and `test_flowers` directories.  
   Run the training script to train the CNN model.

4. **Make Predictions**:  
   Use the trained model to predict the type of flower in new images.

## 📈 Model Performance

- **Epochs**: 25
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Accuracy**: ~92% on the training set.

## ⚡ Example Prediction

Once the model is trained, you can use it to predict the flower type from an input image. The model outputs the predicted flower class, such as **Tulip**, **Daisy**, **Rose**, 

