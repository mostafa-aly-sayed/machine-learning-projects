# Traffic Sign Detection Project #


## 📹 Demo Video

[▶️ Watch Demo from here](https://drive.google.com/file/d/1WzLNezre0_KpKwNhJewsTOiHJcJ4L_j_/view?usp=sharing)

##  Project Summary
This project focuses on developing a real-time traffic sign detection system designed to accurately recognize various traffic signs such as Stop, Speed Limit, and Yield, which are crucial for road safety. The system assists drivers in making informed decisions by detecting signs in real-time using advanced computer vision techniques.
The model leverages YOLOv8 (You Only Look Once), a state-of-the-art object detection algorithm known for its balance between speed and accuracy, making it highly suitable for real-time object detection tasks.

##  Key Features
-   **Real-time detection of traffic signs in both images and videos**.
-   **High accuracy in recognizing signs under varying conditions (lighting, weather, angles)**.
-   **Based on the YOLOv8 model, optimized for performance and fast inference times**.
-   **Detects multiple types of traffic signs and outputs bounding boxes for each**.

##  Purpose
  The purpose of this project is to develop a real-time traffic sign detection system that can assist drivers by accurately recognizing and identifying various traffic signs such as Stop, Speed Limit, and    
  Yield. Also the system is intended to enhance road safety by providing timely and accurate detection of traffic signs in real-world conditions, such as varying weather, lighting, and angles.
  By utilizing advanced computer vision techniques through YOLOv8, the project aims to:
- **Improve driver awareness by automatically detecting traffic signs**.
- **Aid in autonomous driving systems, where traffic sign recognition is crucial for navigation and decision-making**.
- **Enhance road safety, reducing the chances of accidents by making sure drivers are informed of critical road signs in real-time**.

##  Data Preparation
The dataset used for this project consists of images of traffic signs captured in various real-world scenarios. Proper preprocessing is crucial for preparing the data for the model, including resizing the images and normalizing the pixel values to ensure consistent input dimensions and data scaling.
The project demonstrates how deep learning and object detection can be used to build practical solutions for intelligent transportation systems.

## Steps for Data Preparation
- **Data Collection**: Gathering traffic sign images through multiple resources.
- **Annotation**: Using annotation tools such as Roboflow, label the images by drawing bounding boxes around the traffic signs. This step is essential for supervised training since the model learns from these    annotations.

- **Data Splitting**: After annotation, the dataset should be split into training, validation, and testing sets to ensure the model can generalize well on unseen data.

- **Preprocessing**: Resize the images to match the input size of the YOLOv8 model (e.g., 640x640 pixels). Normalization ensures pixel values range between 0 and 1, which speeds up convergence during training.


## Modeling,Training and Testing
- **Model Selection**
YOLOv8: which is efficient for real-time object detection.

- **Training Steps**
	- Preparing Data: Load and preprocess the dataset (resize, normalize).
	- Initializing Model we trained but after we saved it with Its weights.
- **Hyperparameter Tuning**
Hyperparameters that have been tuned (learning rate,batch-size, dropout,optimizer).
Evaluating Performance: Using the validation set to check performance metrics (e.g., mAP).

- **Testing Steps**
	- Evaluating the Test Set to measure the overall performance of the model
  	- Calculating Metrics like precision, recall,and mAP.
	- Visualizing Results: Drawing bounding boxes on test images to visualize predictions.

##  Results
Once trained and tested, the model is capable of detecting traffic signs with high accuracy. Results are visualized with bounding boxes and labels superimposed on the detected signs.

