# Violence-Detection
 This project is designed to detect and alert authorities about violent incidents in school environments in real-time. Utilizes a pretrained RESNET model for image classification and Twilio API for sending notifications. Achieves approximately 93% accuracy on the test dataset.

## Model File

This repository includes the trained model file. Due to file size limitations, the model file is hosted externally.

### Download the Model
[Download the trained model file from Google Drive](https://drive.google.com/file/d/1EemWJT1E76BVUXj1xRK1EkKWmtQBAzQi/view?usp=drive_link)

## Files Uploaded

1. Model_Training.ipynb - This file uses a pretrained RESNET64 model from the fastai library train it on a custom dataset. Its performance is evaluated with various metrics, including plotting the confusion matrix and loss.
2. Violence_Detection_Demo_with_webcam.ipynb - This file demonstrates the trained model's performance on sample images and through a webcam feed. It uses Twilio API to send an SMS if violence is detected.
3. Violence_Detection_with Tello_Drone_Demo.ipynb - This file is used to control the connected Tello drone for showcasing the violence detection model in action.

## Dataset

The dataset used for training this violence detection model is a custom collection consisting of around 1000 images (511 Violent Images and 465 Non-Violent Images). It was created by combining images sourced from Kaggle and images captured manually at our school. It is curated specifically to address potential biases and challenges in violence detection. It includes :

- Images depicting various forms of violence, ensuring representation across different demographics, including scenarios involving girls.
- Positive examples of non-violent interactions, such as friendly gestures (e.g., embracing, shaking hands), to prevent misclassification.
- Sports-related images (e.g., cricket, football) to distinguish between sporting activities and actual violent acts.
- Images captured under various types of lighting conditions to enhance model robustness.
- Images from different perspectives, including CCTV cameras, drones, webcams, etc., to simulate real-world scenarios and improve generalization.

## Contributors
- Shreyal Gupta
- Shivam Gupta
- Intel (This project was made in collaboration with Intel under their AI4Youth Program.)
