# StressLevelDetection

🔍 **Detecting Stress Levels From PPG Sensor Data Using Neural Networks** 🔍

Ever wondered how we can classify stress levels using sensor data? Let’s dive into an exciting project that combines Photoplethysmography (PPG) data, Heart Rate Variability (HRV), and Neural Networks!

### 💡 What You'll Learn:
- Understand **classification** using Artificial Neural Networks (ANN).
- Explore **Photoplethysmography** (PPG) and how it measures Heart Rate Variability (HRV).
- Learn how to **clean and process datasets** effectively.
- Dive into **correlation** and **feature selection** to optimize the model.

### 🔍 **Part 1: Classification**
Classification is a powerful technique where we assign categories or labels to data based on input features. In this project, we tackle a classification problem—**Predicting stress levels from PPG sensor data**. By analyzing subtle changes in heart rate patterns, we can build a model that identifies stress in individuals.

### 🩺 **Part 2: Photoplethysmography & Heart Rate Variability**
PPG is a non-invasive optical technique that detects blood volume changes in the microvascular bed of tissue. Combined with Heart Rate Variability (HRV), we get crucial insights into a person's autonomic nervous system, making it possible to measure stress levels accurately.

### 🧹 **Part 3: Data Cleaning & Processing**
Having clean and well-processed data is critical. We will go through methods to handle noisy or missing data, ensuring the dataset is reliable for building our model. Feature selection and correlation analysis will also play a big role in improving accuracy.

### 📊 **Part 4: The Dataset & Workflow**
We'll be using a rich dataset containing PPG signals and labels corresponding to stress levels. After cleaning, we’ll scale the data using **StandardScaler**, and split it into training and testing sets.

### 🤖 **Part 5: Building the Model**
This is where things get exciting! We’ll create a model using a **Feedforward Artificial Neural Network (FF-ANN)** implemented with the **Sequential Model** in TensorFlow/Keras. ANN’s ability to capture complex patterns in data makes it a perfect tool for this classification problem. We’ll see a steady decrease in both validation and training loss, indicating a well-trained model.

Finally, we’ll test the model on our test data to evaluate its performance and accuracy.
