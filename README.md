<div style="display: flex; align-items: center;">
  <h1>Traffic Sign Classification</h1>
  <img src="https://github.com/Mohammad-Rahmanian/Stop-Sign-Classification/assets/78559411/183d6656-5e08-4d93-982b-a929b07a26f0" alt="Traffic Sign" width="50">
</div>



## Description 📌
This project focuses on developing a deep learning model for traffic sign classification, with a primary goal of accurately identifying stop signs in images. Stop signs play a crucial role in traffic regulation and safety, and an automated system capable of detecting them in images can have significant applications in autonomous vehicles, traffic monitoring, and driver assistance systems.

## Project Goal
The primary objective is to train a machine learning model capable of accurately classifying stop signs in images. Utilizing deep learning techniques, specifically convolutional neural networks (CNNs) and transfer learning, we aim to develop a robust model capable of achieving high accuracy in stop sign detection.

## Techniques Used 🌟
- Transfer Learning: Utilizing pre-trained CNN models as a starting point for training on the specific task of traffic sign classification.
- Convolutional Neural Networks (CNNs): Effective for image recognition tasks, CNNs are used to capture spatial hierarchies of features in images.
- ResNet: Leveraging the depth and effectiveness of ResNet architecture for training deep neural networks, especially in tasks like traffic sign classification.

## Dataset
The dataset used for training and testing the model is available [here](https://drive.google.com/drive/u/5/folders/1RtXgbyWgMzp3rra-Zfx_3Pa98UxqpIBN). It contains images of various traffic signs, organized into separate folders for different types of signs, including stop signs and non-stop signs.

## Usage 📘
1. **Requirements:**
   - Ensure Python is installed.
   - Install dependencies from `requirements.txt`:
     ```
     pip install -r requirements.txt
     ```

2. **Training the Model:**
   - Open `traffic_sign_classification.ipynb` in Jupyter Notebook.
   - Follow instructions to train the model using the provided dataset.

3. **Evaluation and Testing:**
   - Evaluate the model's performance on the test dataset.
   - Use provided functions to make predictions on new images and visualize results.

4. **Deployment:**
   - Deploy the trained model in applications requiring traffic sign detection.
5. **Optimizing Model Performance:**
   - Enhance the model's accuracy by carefully balancing the dataset size with computational resources. Adding more images can improve accuracy and robustness, but it may also increase     
     training time. 

