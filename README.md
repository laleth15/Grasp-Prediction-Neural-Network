# Grasp-Prediction-Neural-Network
A convolutional network to predict successful grasps given a top-down RGB image of the scene. This project uses Unet with MobileNetV3 backbone.

The architecture is inspired by “Searching for MobileNetV3” (https://arxiv.org/pdf/1905.02244.pdf). Intermediate tensor shapes are labeled without batch dimension.

![image](https://github.com/laleth15/Grasp-Prediction-Neural-Network/assets/63454572/1377a463-0b13-4c15-9f00-50b258dcefcc)

To run the code:
1. $python simulator.py (to view the grasp simulator via the Pybullet graphical user interface)
2. $python trainer.py
3. $python evaluate model.py
