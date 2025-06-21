Trash Classification using CNN 🚮🧠
📋 Project Overview
This project focuses on building a Convolutional Neural Network (CNN) model to classify images of different types of trash — including:

Glass

Cardboard

Metal

Paper

Plastic

Trash

The dataset used is the TrashType Image Dataset, organized into folders by class.

📂 Dataset Preparation
The dataset was provided in ZIP format.

It was extracted and organized under /content/dataset/TrashType_Image_Dataset/ with 6 classes.

Data was split into training, validation, and test sets.

🛠️ Tech Stack
Python

TensorFlow / Keras

NumPy

Matplotlib & Seaborn

Scikit-learn

📊 Project Steps
✅ Dataset extraction and structure check
✅ Data visualization & class distribution
✅ CNN model building & training
✅ Model evaluation on unseen test set
✅ Confusion matrix and performance metrics

⚙️ Model Architecture
3 Convolutional layers with MaxPooling

1 Dense layer with Dropout for regularization

Output layer with Softmax for multi-class classification

🚀 Results
Current model accuracy: ~65%

Planned improvements:

Deeper CNN model

Transfer learning (MobileNetV2, ResNet)

Advanced data augmentation
