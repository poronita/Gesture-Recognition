# Gesture Recognition for Smart TVs

## Table of Contents
* <span style="color:purple">[Objective](#objective)</span>
* <span style="color:purple">[Background](#background)</span>
* <span style="color:purple">[About the Data](#about-the-data)</span>
* <span style="color:purple">[Used Technology](#used-technology)</span>
    - <span style="color:green">[Convolutions + RNN](#convolutions--rnn)</span>
    - <span style="color:green">[3D Convolutional Network (Conv3D)](#3d-convolutional-network-conv3d)</span>
    - <span style="color:green">[Generators](#generators)</span>
* <span style="color:purple">[Conclusion](#conclusion)</span>
* <span style="color:purple">[Acknowledgment](#acknowledgment)</span>
* <span style="color:purple">[Contact](#contact)</span>

## Objective
The aim of this project is to develop a gesture recognition system for smart TVs using deep learning architectures.

## Background
In the era of smart technology, enhancing user experience is crucial. Gesture recognition offers an intuitive way for users to interact with their devices, eliminating the need for traditional remotes.

## About the Data
The dataset comprises video recordings of hand gestures, including thumbs up, thumbs down, left swipe, right swipe, and stop gestures. Each gesture corresponds to a specific command for controlling the TV.

## Used Technology
- Python
- TensorFlow/Keras
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- 3D Convolutional Neural Networks (Conv3D)

### Convolutions + RNN
The Convolutions + RNN architecture involves passing video frames through a Convolutional Neural Network (CNN) to extract features, followed by feeding the sequence of feature vectors into a Recurrent Neural Network (RNN) for temporal analysis. This architecture is effective for processing sequential data like videos.

### 3D Convolutional Network (Conv3D)
A 3D Convolutional Network (Conv3D) extends 2D convolutions to process 3D data, such as video sequences. It operates by convolving filters in three dimensions (x, y, and z), making it suitable for capturing spatiotemporal features in videos.

### Generators
Generators are essential for creating data pipelines in deep learning projects. They allow for the efficient feeding of data to models in batches. In this project, custom generators are used to preprocess batches of videos, including steps like cropping, resizing, and normalization, before feeding them into the model during training.

## Conclusion
In this project, we developed a gesture recognition system for smart TVs using deep learning architectures, specifically Convolutions + RNN and Conv3D. By leveraging these technologies and custom generators, we achieved accurate recognition of hand gestures, enabling users to control their TVs seamlessly without the need for traditional remotes.

## Acknowledgment
I acknowledge the contribution of Professor Raghavan and Snehansu, a research engineer at American Express, for introducing the problem statement and providing valuable guidance throughout the project. I also extend my gratitude to Upgrade Academy for their support and resources.

## Contact
For any inquiries or feedback, please contact:
- <span style="color:purple">[Prathvi Bhatti](mailto:theprathvibhatti@gmail.com)</span>
- <span style="color:purple">[@poronita](https://github.com/poronita)</span>
