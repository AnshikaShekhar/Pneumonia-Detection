// ANSHIKA SHEKHAR
This project is a pneumonia classification web app that leverages deep learning to detect pneumonia from chest X-ray images. It uses a pre-trained TensorFlow Keras model and provides predictions through an intuitive web interface built with Streamlit.

Key Features:
Image Upload and Preprocessing: Users upload X-ray images, which are automatically resized and normalized for prediction.
Deep Learning Model: A TensorFlow Keras model classifies the image as either Normal or Pneumonia.
Confidence Score: The app provides a confidence score with the prediction, ensuring transparency.
Healthcare Insights: If pneumonia is detected, the app suggests actionable steps for care.
User-Friendly Interface: The lightweight Streamlit interface makes the app accessible for non-technical users.
Technical Highlights:
Custom Layer Handling: The app addresses compatibility challenges with a custom implementation of TensorFlow’s DepthwiseConv2D.
Background Customization: Adds a visual appeal by setting a custom background image.
Scalability: Can be extended to detect other diseases or handle multi-class classification.
