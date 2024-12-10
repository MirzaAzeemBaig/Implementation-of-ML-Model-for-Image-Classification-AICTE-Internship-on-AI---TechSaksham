# Implementation of Machine Learning Model for Image Classification-AICTE-Internship

The application titled "Implementation of Machine Learning Model for Image Classification" serves as a Streamlit platform that incorporates the MobileNetV2 architecture alongside a CIFAR-10 model dedicated to image classification tasks. Users possess the capability to upload images and obtain predictions accompanied by corresponding confidence scores from either of the models. The application is equipped with a well-designed navigation bar, facilitating effortless transitions between different functionalities and delivering real-time results, thereby rendering it suitable for both educational and practical applications.

Key Features

Support for Dual Models:

1. MobileNetV2 (ImageNet): This model is trained to identify 1,000 distinct categories derived from the ImageNet dataset, encompassing common objects, various animal species, and different types of vehicles.
   
2. Custom CIFAR-10 Model: This model is specifically tailored for the classification of images into one of ten designated categories, which include airplanes, automobiles, and birds.

User-Friendly Interface:

1. Navigation Bar: The application features a streamlined sidebar menu, allowing users to switch effortlessly between the MobileNetV2 and CIFAR-10 models.
   
2. Real-Time Classification: Users can upload an image and receive immediate predictions along with their respective confidence scores.

Improved Functionality:

1. Model Performance Optimization: The application has been enhanced to ensure faster inference times and improved accuracy rates for the models.
   
2. Visualization Tools: The application includes instruments for visualizing model predictions and allows for the comparison of performance metrics.

Educational and Practical Application:

This application serves as an excellent resource for individuals seeking to acquire knowledge about deep learning models and their operational effectiveness. Moreover, it is practical for scenarios where image classification is required.

Getting Started

Prerequisites:

1. Python version 3.7 or higher
2. Access to a web browser


Installation

Clone the repository:

git clone https://github.com/MirzaAzeemBaig/Implementation-of-ML-Model-for-Image-Classification-AICTE-Internship-on-AI---TechSaksham.git

cd Implementation-of-ML-Model-for-Image-Classification-AICTE-Internship-on-AI-TechSaksham

Create and activate a virtual environment:

python -m venv venv

source venv/bin/activate   # On Windows use `venv\Scripts\activate`

Install the required packages:

pip install -r requirements.txt

Start the Streamlit app:

streamlit run Application.py

Open the app: The app will open in your default web browser. If not, navigate to http://localhost:8501



Contributing

Individuals are encouraged to fork the repository, raise issues, or submit pull requests to contribute to the development of this project.

Acknowledgements

1. Streamlit
2. TensorFlow
3. Community Support: Both documentation and community forums are available to assist with troubleshooting and knowledge sharing among users.
