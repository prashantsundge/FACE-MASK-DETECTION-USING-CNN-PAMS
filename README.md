
# Face Mask Detection CNN Project

## Author: Prashant Sundge

### Index

1. Importing Libraries 
2. Using Kaggle API to Connect with Kaggle and Fetch the Datasets
3. Using ZipFile Module to Extract the Data
4. Creating Classification Labels 
5. Displaying Sample Images with Mask and Without Mask 
6. Image Processing 
    - Image Resize 
    - Converting Image to RGB
    - Converting Image to NumPy Array
7. Converting All Images and Labels to NumPy Format 
8. Splitting Data into Training and Testing Sets 
9. Scaling Data
10. Building Convolutional Model 
11. Compiling Neural Network Model 
12. Model Evaluation
13. Plotting Model's Loss and Accuracy 
14. Creating Predictive System to Test the Images



This project focuses on the development of a Convolutional Neural Network (CNN) for detecting the presence of face masks in images. The goal is to accurately identify whether individuals are wearing masks or not, which is crucial for enforcing safety measures, particularly during the COVID-19 pandemic.

The project begins with importing necessary libraries and accessing datasets using the Kaggle API. Data extraction is facilitated using the ZipFile module, followed by the creation of classification labels.

Sample images depicting individuals with and without masks are displayed to provide insight into the dataset. Image processing techniques such as resizing, conversion to RGB format, and conversion to NumPy arrays are applied to prepare the data for training.

All images and labels are then converted into NumPy format for further processing. The dataset is split into training and testing sets, and the data is scaled to optimize model performance.

A Convolutional Neural Network architecture is constructed to learn and detect patterns in the images. The model is compiled, trained, and evaluated using appropriate metrics.

Model performance is visualized through plots showcasing loss and accuracy during training. Finally, a predictive system is created to test the model's performance on new images.

This project leverages the power of deep learning and computer vision to contribute to the broader effort of ensuring public safety through automated face mask detection.


### Environment

- cv2
- google.colab.patches
- PIL
- sklearn.model_selection
- zipfile
- os
- numpy
- matplotlib.pyplot
- Keras
- TensorFlow
- Python 3.0

### Project Published on

[Link to Kaggle Project](https://www.kaggle.com/prashantkumarsundge/face-mask-detection-pams)

---

Feel free to make any necessary adjustments or additions to this README file!
