# SmartGarbage AI – Garbage Classification for Smart Cities

## About the Project
SmartGarbage AI is a Deep Learning-based web application that automatically classifies garbage images into six categories. It aims to support proper waste segregation and smart waste management.

## Garbage Categories
- Cardboard
- Glass
- Metal
- Organic
- Paper
- Plastic

## Technologies Used
- Python
- TensorFlow
- Keras
- MobileNetV2
- Flask
- NumPy
- SQLite
- HTML
- CSS
- Bootstrap
- JavaScript

## Deep Learning Model
I used MobileNetV2 with Transfer Learning for image classification. The model is trained to recognize six categories of garbage.

## How It Works
1. User uploads a garbage image.
2. The image is resized to 224 × 224 pixels.
3. Image pixels are normalized.
4. MobileNetV2 processes the image.
5. The system predicts the garbage category and confidence.
6. Basic disposal advice is displayed.
7. Prediction details are stored in an SQLite database.

## Features
- Image-based garbage classification
- Six garbage categories
- Prediction confidence
- Disposal recommendations
- Prediction history
- Delete individual or all history records

## Model Performance
Achieved approximately **83% validation accuracy** on 703 validation images.

## How to Run
1. Clone or download this repository.
2. Install the required dependencies:
   `pip install -r requirements.txt`
3. Run the application:
   `python app.py`
4. Open the Flask local URL in your browser.

## Future Scope
- Add more garbage categories.
- Improve model accuracy.
- Add unknown-object detection.
- Integrate with smart waste bins.

## Developed By
**Triveni Jadhav**

MCA Student | Deep Learning Project
