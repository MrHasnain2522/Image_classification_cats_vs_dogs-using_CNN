# Project title:
 🐾Image classifier cats vs dogs using cnn model

# intro:
      This project uses a Convolutional Neural Network (CNN) to classify images of cats and dogs. It's a binary classification task where the model learns,
      to distinguish between cat and dog features by training on labeled images.
      CNNs are powerful for image classification tasks because they automatically extract spatial features such as edges, textures, and shapes,
      which are crucial for identifying objects in photos. This project is a popular deep learning exercise and demonstrates how to apply AI in real-world visual tasks.
## 🧠 CNN Model Architecture:
- Input Layer (e.g., 150x150x3)
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten
- Dense → ReLU
- Dropout (for regularization)
- Dense → Sigmoid (binary classification)

## 🛠️ Tools & Libraries:
- Python
- TensorFlow / Keras
- NumPy, pandas
- Matplotlib, seaborn
- Jupyter Notebook / Google Colab

## 🚀 Project Workflow

1. Load and preprocess image dataset
2. Normalize image pixel values
3. Split data into training, validation, and test sets
4. Build CNN model using Keras Sequential API
5. Train the model and evaluate accuracy/loss
6. Test the model on unseen images
7. Visualize performance and predictions

## ✅ Results

- Training Accuracy: 90
- Validation Accuracy: 87
- Final Test Accuracy: ~XX%
