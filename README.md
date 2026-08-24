
A simple image classification web application built using Python, TensorFlow, and Streamlit.

#Info

- Upload an image
- Classify the image using MobileNetV2
- Display the top 3 predictions
- Show the confidence score for each prediction

# What i used to make it:

- Python
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- NumPy
- Pillow
- Streamlit



The application uses a pre-trained MobileNetV2 model trained on ImageNet.

Uploaded images are:

1. Resized to 224 × 224 pixels
2. Preprocessed for MobileNetV2
3. Passed through the model
4. Decoded into the top 3 predicted classes

#to run:


Install the required libraries:

```bash
pip install tensorflow opencv-python numpy pillow streamlit
