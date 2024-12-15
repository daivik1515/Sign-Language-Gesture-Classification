**🌐 Project Overview**

This project aims to create a robust, deep learning-based system for classifying sign language gestures in real time, facilitating improved communication for individuals with hearing impairments. By implementing and comparing several CNN architectures, including LeNet, VGG, and ResNet, the project will assess which model performs best in identifying a variety of sign gestures across different datasets. The system leverages transfer learning and hyperparameter optimization to achieve high accuracy and adaptability across diverse environments.

**📂 Datasets**

To build a well-rounded, versatile model, we've selected three datasets that represent a wide range of gestures and sign languages:

**Sign Language Digits Dataset**

Samples: 2,062 images

Resolution: 100x100

[Sign Language Digits Dataset](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset)

**Indian Sign Language Dataset**

Samples: 42,000 images

Resolution: 128x128

[Indian Sign Language Dataset](https://www.kaggle.com/datasets/vaishnaviasonawane/indian-sign-language-dataset)

**Hand Gesture Recognition Dataset**

Samples: 3,259 images

Resolution: 240x215

[Hand Gesture Dataset](https://www.kaggle.com/datasets/sarjit07/hand-gesture-recog-dataset)

Model performance is then evaluated using accuracy, precision, recall, F1 score, and ROC curve, allowing a comprehensive comparison across architectures to determine the most effective approach for gesture recognition.

**📊 Evaluation Metrics**

To thoroughly evaluate model performance, we’ll be assessing each CNN on:

- **Accuracy**
 
- **Precision**
  
- **Recall**
  
- **F1 Score**
  
- **ROC Curve**

## Requirements to run the code

### Libraries used:
- PyTorch: Deep learning library for building neural networks.
- torchvision: PyTorch's computer vision library.
- Pillow: Python Imaging Library used for image processing tasks.
- pandas: Data manipulation and analysis library.
- opencv-python: OpenCV library for computer vision tasks.
- scikit-learn: Machine learning library for various algorithms and tools.
- seaborn: Statistical data visualization library based on matplotlib.
- matplotlib: Plotting library for creating static, animated, and interactive visualizations in Python.
- numpy: Numerical computing library for handling arrays and matrices.
- beautifulsoup4: Library for web scraping and parsing HTML and XML documents.
- bs4: Alias for BeautifulSoup4, used for web scraping tasks.
  
## To run the ipynb files

The files can be run directly after ensuring all the necessary libraries are present on colab. 
We access the dataset directly from the dropbox, we unzip the data inside our code.

## To train and validate model

The files can be run directly for training and validating models for each architecture.
We access the dataset directly from the dropbox, we unzip the data inside our code.

## Instructions on how to run the pre-trained model on the provided sample test dataset

You don't need anything, just open the code in collab and run the code as we have provided link to the dataset from dropbox identical to the data from kaggle.

