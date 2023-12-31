# Human-Action-Recognition-Using-Deep-Learning
![Picture11](https://github.com/km-adarsh/Human-Action-Recognition-Using-Deep-Learning/assets/65649644/4be12708-d3c1-452e-b6a7-ac6f9987f87f)



## Overview

**Human Activity Recognition** aims to recognize human actions from videos, decode stance and movement information using **Mediapipe**, and categorize actions using **LSTM**.

## Methodology

We leverage the following tools and technologies:

1. **TensorFlow**: Used for building and training the deep learning model, especially the LSTM network.

2. **OpenCV-python**: Applied for video processing, frame extraction, and other computer vision tasks.

3. **OS with minimum 8GB RAM**: Ensures efficient execution of the project, especially during training and testing phases.

4. **Mediapipe framework**: Employed for robust pose estimation, enabling the extraction of human stance and movement information from videos.

5. **Python programming language**: The primary language for implementing the entire project.

6. **Jupyter notebook**: Provides an interactive and visual environment for running and experimenting with code.

## Dataset

The dataset used for training and testing the model comprises 90 sequences, with 30 sequences for each of the following six actions:

- DrinkingWater
- PushUps
- Running
- Squats
- Walking
- Standing

Each sequence consists of 30 frames extracted from three videos per action, presenting various challenging conditions such as shifting lighting, changing camera angles, and occlusion.
[Human_Action_Recognition_Mediapipe_LSTM.ipynb](https://github.com/km-adarsh/Human-Action-Recognition-Using-Deep-Learning/blob/main/Human_Action_Recognition_Mediapipe_LSTM.ipynb) contains code that establishes directories and gathers pose data utilizing the Mediapipe framework, OpenCV, and a holistic model. It systematically organizes the data by actions, video numbers, and sequences, laying the groundwork for human activity recognition.

## Performance

On our custom dataset, the proposed method demonstrates cutting-edge performance with a maximum accuracy of 96.3%. Comprehensive tests were conducted to evaluate the model's robustness in scenarios like changing lighting conditions, shifting camera angles, and occlusion.


![Figure 10](https://github.com/km-adarsh/Human-Action-Recognition-Using-Deep-Learning/assets/65649644/9e1eed25-bfd7-41e2-a504-58550064620c)



## Contributors

Nagesh U B (Assistant Professor)  
Abhishek V Doddagoudra, Adarsh K M, Mayoori K Bhat, Shreya L (UG Students)  
Department of Information Science and Engineering  (2019 - 2023)  
Alva’s Institute of Engineering and Technology, Mangalore, India


Feel free to experiment, contribute, and adapt the code to suit your specific needs.

We hope this repository proves valuable for your human activity recognition projects!
