# Plant-leaf-disease-detection-cnn
🌿 Plant Leaf Disease Detection using CNN  This project uses Deep Learning (CNN) to automatically detect plant leaf diseases from images. The model is trained on the PlantVillage dataset and can predict disease with high accuracy.

This system allows users to upload any leaf image and instantly get:

Plant name

Disease type

Confidence score

🚀 Tech Stack

Python

TensorFlow / Keras

CNN (Convolutional Neural Network)

NumPy

Matplotlib

Pillow (Image Processing)

KaggleHub (Dataset API)

Google Colab (GPU Training)

✨ Key Features

✅ Automatic dataset download from Kaggle
✅ Image preprocessing & normalization
✅ Data augmentation (rotation, zoom, flip)
✅ Custom CNN architecture
✅ Multi-class classification
✅ Training + validation accuracy tracking
✅ Accuracy & loss visualization
✅ Model saving (.keras)
✅ Real-time image upload prediction
✅ GPU accelerated training
✅ Fully end-to-end pipeline

🧠 Model Architecture

The CNN model consists of:

3 × Conv2D layers (32 → 64 → 128 filters)

MaxPooling layers

Flatten layer

Dropout (0.5) for regularization

Dense (256 neurons)

Softmax output layer (15 classes)

📊 Model Summary

![Accuracy](Output1.png)

📈 Training Results
Final Performance

Train Accuracy → 93.21%

Validation Accuracy → 93.89%

Low validation loss

No major overfitting

Accuracy & Loss Graph

![Graph Accuracy](Output2.png)

🔍 Prediction Example

The model successfully predicts:

Plant → Pepper bell
Disease → Bacterial spot
Confidence → 100%

![Model](Output3.png)

📂 Project Structure
plant-leaf-disease-detection/
│
├── plant_disease_model.ipynb
├── plant_leaf_disease_model.keras
├── class_names.npy
├── requirements.txt
├── README.md
├── results.png

▶ How to Run
Install dependencies
pip install -r requirements.txt

Run training
python plant_disease_model.py


OR open in Google Colab.

📦 Dataset

PlantVillage dataset from Kaggle
Contains thousands of labeled leaf images across multiple crops and diseases.

💡 Future Improvements

Transfer Learning (MobileNet/ResNet)

Streamlit web app

Mobile app deployment

Real-time camera detection

Model optimization

🎯 Learning Outcomes

Through this project, I learned:

CNN architecture design

Image preprocessing

Data augmentation

Model training & evaluation

Overfitting handling

Deployment-ready ML pipeline


👨‍💻 Author
Harshdeep Srivastava
B.Tech CSE (AI)
Deep Learning & Computer Vision Enthusiast
