# MSTAR-Target-Classification
Project Overview
The project uses the MSTAR (Moving and Stationary Target Acquisition and Recognition) 8 class dataset from kaggle to perform SAR image classification.The aim is to achieve target classification of different vehicles using machine and deep learning algorithms and tuning parameters too find the best fit. SAR imagery consists of X-band radar images which consists of speckle noise and is complex to classify.

# Key Features & Technologies
- Dataset: MSTAR (Public SAR dataset)
- Model: Logistic Regression, SVM, CNN, XG-Boost, Decision Tree, Random Forest
- Languages: Python
- Libraries: NumPy, OpenCV, TensorFlow / PyTorch, Scikit-learn, Matplotlib
- Notebook: Jupyter (.ipynb)
  
# Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   
# Install Dependecies: 
matplotlib.pyplot, numpy, cv2, sklearn, tensorflow, xgboost, optuna, streamlit.

# Run the notebook:
Open notebook.ipynb in Jupyter Notebook or Google Colab.
Follow the cells step by step.

# Dataset:
Download MSTAR from https://www.kaggle.com/datasets/atreyamajumdar/mstar-dataset-8-classes/code.
Install the zip in google drive and import it in collab to unzip.

# Data Science Focus

# Approach
- Classification of image was done using different algorithms in which logistic regression 97% and svm 96% give the best accuracies then CNN 94% and xg-boost 95%, decision tree was not very accurate with only 71% accuracy and Randome forest with 84%.

# Data Handling
- Dataset used: MSTAR (Public Dataset) — includes SAR images of military vehicles captured under different conditions. Dataset was loaded, normalized, filtered and resized for model and hyperparameter tuning was done to find the best fit. Confusion metrics and ROC curve was plotted to check the reliability of the model.

# Model Explainability
- Included layer visualizations and filter activations for better insight into what the model learns.

# Google Collab Link
https://colab.research.google.com/drive/153dIVUZET4mdetpDZSPTPO8ZzJNzYRU1?usp=sharing
