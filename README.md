Image Classification with CIFAR-10 and MobileNetV2


This repository contains an AI-driven image classification project that leverages both custom and pre-trained models for real-time predictions. The project is implemented using Python, TensorFlow, and Streamlit, with a user-friendly web app for deployment.

Features
CIFAR-10 Model: A custom-trained Convolutional Neural Network (CNN) for classifying images into 10 categories.
MobileNetV2 Integration: A pre-trained model capable of classifying images into 1,000 categories using ImageNet.
Interactive Web App: A Streamlit-based interface for real-time image uploads and predictions.
Repository Structure
Image_Classification_using_CIFAR-10_Dataset.ipynb: Notebook detailing model training and evaluation.
app.py: Streamlit app integrating CIFAR-10 and MobileNetV2 models.
cifar10_model.h5: Pre-trained CIFAR-10 model.
requirements.txt: List of dependencies to set up the environment.
test_data.zip: Sample images for testing.
Live App
Try the live app here: Image Classification App

Installation : 

Clone this repository:
bash
Copy code
git clone https://github.com/anegouni-bhanuprasad-goud/CNN-Image-Classification-Streamlit-App
Navigate to the project directory:
bash
Copy code
cd CNN-Image-Classification-Streamlit-App
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the app locally:
bash
Copy code
streamlit run app.py
Future Enhancements
Support for custom datasets.
Optimizations for edge devices using model pruning and quantization.
Improved user interface with image preprocessing options.
License
This project is licensed under the MIT License.

Feel free to fork and contribute to the project. Happy coding!
