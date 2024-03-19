# Traffic Sign Classification

!Traffic Sign

## Description
This project focuses on developing a deep learning model for traffic sign classification, with a primary goal of accurately identifying stop signs in images. Stop signs play a crucial role in traffic regulation and safety, and an automated system capable of detecting them in images can have significant applications in autonomous vehicles, traffic monitoring, and driver assistance systems.

## Project Goal
The primary objective is to train a machine learning model capable of accurately classifying stop signs in images. Utilizing deep learning techniques, specifically convolutional neural networks (CNNs) and transfer learning, we aim to develop a robust model capable of achieving high accuracy in stop sign detection.

## Techniques Used
- Transfer Learning: ![Transfer Learning](https://img.icons8.com/ios-filled/50/000000/transfer-between-users.png%29) 
  Utilizing pre-trained CNN models as a starting point for training on the specific task of traffic sign classification.
- Convolutional Neural Networks (CNNs): ![Convolutional Neural Networks](https://img.icons8.com/ios-filled/50/000000/neural-network.png%29) 
  Effective for image recognition tasks, CNNs are used to capture spatial hierarchies of features in images.
- ResNet: ![ResNet](https://img.icons8.com/ios-filled/50/000000/neural-network.png%29) 
  Leveraging the depth and effectiveness of ResNet architecture for training deep neural networks, especially in tasks like traffic sign classification.

## Dataset
The dataset used for training and testing the model is available [here](https://drive.google.com/drive/u/5/folders/1RtXgbyWgMzp3rra-Zfx_3Pa98UxqpIBN%29). It contains images of various traffic signs, organized into separate folders for different types of signs, including stop signs and non-stop signs.

## Usage
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

## License
This project is licensed under the MIT License: !MIT License

## Credits
Icons made by !Icons8.
