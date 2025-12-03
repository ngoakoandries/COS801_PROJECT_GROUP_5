# Deep Learning Model for Sign Language Translation

 This project aims to classify American Sign Language (ASL) alphabet gestures using three classification approaches:

- SVM + HOG (Support Vector Machines with Histogram of Oriented Gradients)
  
- CNNs (Convolutional Neural Networks)

- ResNet-50

# Dataset 
The dataset comprises of diverse images from real colour, grayscale images, line drawings, sketches, and artistic renderings of hand gestures. 
The link to the dataset is https://huggingface.co/datasets/Marxulia/asl_sign_languages_alphabets_v03


# Project Structure

<pre> COS801_PROJECT_GROUP_5/ 
 
 ├── COS801_Project_V2.ipynb # Main notebook: preprocessing pipelines, model training (SVM + HOG, CNN, ResNet-50) 
 
 ├── report_figures/ # Plots, confusion matrices
 
 ├── requirements.txt # Python dependencies 
 
 └── README.md # Project documentation </pre>


# Pipeline Overview
1. The complete recognition pipeline includes
2. Image preparation & preprocessing
3. Feature extraction (HOG or CNN-based)
4. Model training & evaluation
5. Performance visualization and comparison

# Installation and Setup

### 1. Clone the Repository
- git clone https://github.com/ngoakoandries/COS801_PROJECT_GROUP_5.git
- cd COS801_PROJECT_GROUP_5

### 2. Create a Virtual Environment (Python 3.11)

    - python3.11 -m venv venv

### 3. Activate the Virtual Environment
  Linux / macOS:
  
    - source venv/bin/activate

  Windows (PowerShell):
  
    - venv\Scripts\Activate.ps1
  
### 4. Install Dependencies

    - pip install -r requirements.txt
  
## Results Summary
Overall accuracy: 
- SVM + HOG: 29.32%
- Standard CNN: 25.74%
- ResNet-50: 85.75% (best performance)
