Brain Tumor Classification using AI

This project focuses on building an AI-based solution for multi-class brain tumor classification using deep learning techniques. It aims to accurately detect and classify different types of brain tumors—such as Glioma, Meningioma, and Pituitary tumors—from MRI images.

Project Highlights

Multi-class classification of brain tumors
Deep Learning with CNN/Transfer Learning (e.g., VGG16, ResNet50)
High accuracy and performance on MRI datasets
Trained on labeled brain tumor datasets (e.g., Kaggle/Harvard datasets)
Performance evaluation using accuracy, precision, recall, and confusion matrix
Technologies Used

Python
TensorFlow / Keras
OpenCV
NumPy & Pandas
Matplotlib & Seaborn
Dataset

The model is trained on a publicly available brain MRI dataset containing:

Glioma Tumor
Meningioma Tumor
Pituitary Tumor
No Tumor (optional)
Dataset Source: https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection

Project Structure

├── data/ ├── models/ ├── notebooks/ ├── utils/ ├── brain_tumor_classifier.py ├── README.md └── requirements.txt

Results

Validation Accuracy: 95%+
Precision, Recall: Greater than 90%
Confusion Matrix showing distinct class separation
How to Run

git clone https://github.com/yourusername/brain-tumor-ai.git cd brain-tumor-ai pip install -r requirements.txt python brain_tumor_classifier.py

Future Improvements

Real-time MRI image prediction via web app
Model optimization for mobile deployment (ONNX/TFLite)
Integration with Grad-CAM for explainability
