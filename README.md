# Mini-Detecto: AI-Powered Object Detection Robot

## Project Description
Mini-Detecto is an advanced mechatronics project demonstrating object classification and robotic interaction using machine learning techniques.

## Objective
Develop a robotic system capable of identifying two specific objects and pointing to them using servo motors, leveraging different machine learning approaches.

## Machine Learning Approaches

### 1. Feed Forward Neural Network (ANN)
- Architecture: Dense layers with sigmoid activation
- Success Rate: 1.75 (175%)
- Characteristics:
  - Simple neural network structure
  - Binary classification technique
  - Preliminary machine learning approach

### 2. Convolutional Neural Network (CNN)
- Architecture:
  - Convolutional layers: 16, 32, 64 filters
  - Multiple MaxPooling layers
  - Dense layers with ReLU activation
- Performance:
  - Training Accuracy: 95.5%
  - Validation Accuracy: 96.09%
  - Test Success Rate: 90%

### 3. Transfer Learning with ResNet50
- Base Model: Pre-trained ResNet50 (ImageNet weights)
- Modifications:
  - Frozen convolutional base
  - Custom fully connected layers
- Performance:
  - Success Rate: 95%
  - Best Validation Accuracy: 97.79%

## Dataset Characteristics
- Total Images: 1,783
- Classes: 2 (e.g., Apple and Banana)
- Data Distribution:
  - Training: 60%
  - Validation: 30%
  - Testing: 10%

## Hardware Configuration
- Microcontroller: Arduino
- Actuators: 2x Servo Motors
- Sensing: USB Camera/Webcam
- Processing Unit: Laptop/PC

## Technical Features
- Real-time object classification
- Robotic arm pointing mechanism
- Multi-approach machine learning comparison
- Adaptable to different object pairs

## Performance Metrics
- Calculation Method:
  ```
  Success Rate = (N1 + N2) / 20
  N1: Correct predictions for Object 1
  N2: Correct predictions for Object 2
  ```

## Recommended Improvements
- Implement learning rate scheduling
- Add early stopping mechanism
- Enhance data augmentation
- Integrate dropout layers for regularization

## Project Metadata
- Course: MTE 438: AI in Mechatronics and Robotics
- Institution: Faculty of Engineering
- Department: Mechatronics Engineering
- Instructor: Dr. Haitham El-Hussieny

## Deliverables
1. Demonstration video
2. Comprehensive source code
3. Comparative analysis of ML approaches
