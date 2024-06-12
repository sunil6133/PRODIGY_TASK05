# PRODIGY_TASK-05


Fruits-Vegetable Classification and Calorie Estimation
This project utilizes machine learning and web scraping techniques to classify images of fruits and vegetables and estimate their calorie content. The application is built using Streamlit, a Python library for building interactive web applications, and leverages a pre-trained deep learning model for image classification.

Objective
The primary objective of this project is to create an easy-to-use web application that allows users to upload images of fruits and vegetables, classify them into their respective categories, and provide an estimate of their calorie content per serving. The application aims to promote healthy eating habits by providing users with nutritional information about various food items.

Features
Image Classification: The application classifies uploaded images into either fruits or vegetables using a pre-trained deep learning model.
Calorie Estimation: Upon classification, the application retrieves the estimated calorie content of the recognized food item from an online source using web scraping techniques.
Interactive Interface: The web application provides an intuitive and user-friendly interface for users to upload images, view classification results, and access calorie information.

Usage
Upload Image: Users can upload an image of a fruit or vegetable using the file uploader provided on the web application.
Image Classification: Upon uploading an image, the application automatically classifies it into either a fruit or vegetable category.
Calorie Estimation: After classification, the application fetches the estimated calorie content of the recognized food item from an online source.
View Results: Users can view the classification result (fruit or vegetable) and the estimated calorie content per serving displayed on the web application.
Dependencies
Streamlit: A Python library for building interactive web applications.
PIL (Python Imaging Library): A library for opening, manipulating, and saving many different image file formats.
requests: A library for making HTTP requests to fetch web page content.
BeautifulSoup: A library for parsing HTML and XML documents.
Install the required dependencies using pip:

pip install streamlit pillow requests beautifulsoup4
Running the Application
To run the application, execute the following command in your terminal:


streamlit run app.py
The application will launch in your web browser, allowing you to upload images and view classification results interactively.
