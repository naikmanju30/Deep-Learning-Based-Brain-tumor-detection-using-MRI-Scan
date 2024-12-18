# Deep-Learning-Based-Brain-tumor-detection-using-MRI-Scan

Overview
This project implements a deep learning-based approach for detecting and classifying brain tumors from MRI images. Utilizing a Convolutional Neural Network (CNN), the system can classify images into one of four categories: glioma, meningioma, no tumor, and pituitary tumor. The web interface, built with Flask, allows users to upload MRI images and get real-time predictions.

Features
Accurate Classification: Classifies MRI images into tumor and non-tumor categories with high precision.
Web Interface: Flask-based interface for easy image uploads and real-time predictions.
Automated Preprocessing: Includes image resizing, normalization, and RGB conversion.
Extensible: Designed to incorporate additional tumor types or imaging modalities.
Technologies Used
Programming Language: Python
Frameworks: TensorFlow, Keras, Flask
Libraries: OpenCV, NumPy, Pandas, Matplotlib, Pickle
Tools: Jupyter Notebook, HTML/CSS for the frontend
Dataset
The model is trained on a publicly available MRI dataset organized into categories:

Glioma
Meningioma
No Tumor
Pituitary
Ensure the dataset is stored in the mri-images directory as per the folder structure defined in the project.

Installation and Setup
Requirements
Python 3.8+
Required Python libraries: Listed in requirements.txt

Model Details
The model architecture includes:

Convolutional layers for feature extraction
MaxPooling layers for dimensionality reduction
Dense layers for classification
Trained with advanced preprocessing and hyperparameter tuning to optimize performance.

Usage
Upload MRI images via the web interface to classify tumor types.
Explore the Flask API endpoint /get-random-image to fetch random MRI images for testing.
Future Enhancements
Integrate multi-modal imaging (e.g., CT scans).
Add interpretability features like heatmaps for prediction explanations.
Improve UI for better user experience.
Contributors
Manjunath Ravi Naik – Project Development and Model Training
This README covers all necessary aspects of your project. Let me know if you'd like me to generate a requirements.txt file or any additional content!






