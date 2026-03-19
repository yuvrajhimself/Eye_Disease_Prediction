# Eye_Disease_Prediction Using Deep Learning

This project is based on building an eye disease prediction system using deep learning. Different models like CNN, MobileNetV3 and ResNet are trained and compared to find which one performs the best on the dataset. The final selected model is then used to make real-time predictions through a Streamlit web application.

The goal of this project is to understand how different deep learning architectures behave on the same problem and how we can choose the most efficient model.

## Features

>Implementation of multiple models (CNN, MobileNetV3, ResNet)

>Comparison of model performance

>Real-time prediction using Streamlit

>Simple and easy to use interface

## Tech Stack

>Python

>TensorFlow / Keras

>Streamlit

## Project Structure

train/              training dataset  
test/               testing dataset
val/               validation dataset  
models/             saved models  
app.py              streamlit app  
requirements.txt    dependencies  
README.md  


## Models Used

I have used three different models in this project:

CNN as a baseline model

MobileNetV3 for efficient and faster predictions

ResNet for deeper feature extraction

All models were trained on the same dataset and evaluated using accuracy and other metrics. The best performing model was selected for deployment.

## How to Run

git clone <repo-link>
cd <repo-name>
pip install -r requirements.txt
streamlit run app.py
Results

The models were compared based on performance, and the best one was used for prediction in the web app.


## Future Improvements

>Use a larger dataset

>Add more disease categories

>Improve model accuracy

>Deploy the project online

## Disclaimer

This project is only for learning purposes and should not be used for medical diagnosis.