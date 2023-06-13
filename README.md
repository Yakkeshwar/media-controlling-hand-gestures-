# Gesticulation based media player controller using deep learning

## Contact Me on Linkedin:https://www.linkedin.com/in/yakkeshwar-r-945877202/

### A Web Application to control media player using Hand gesture

The main goal is to interface with the computer system using hand gestures, which are the most natural form. The objective of this project is to develop a web application that makes use of the camera on your smartphone to let you control any media player application without the need for a remote or extra hardware. It would apply these gestures in a way that makes them simple, quick, effective, and certain to elicit a prompt response. By enabling remote device control, it improves your productivity and makes your life more convenient and comfortable.

The suggested approach enables remote hand gesture control of the media player. 
1. To create datasets, raw photos are gathered and converted to black and white images using OpenCV. 
2. For the purpose of feature extraction and classification, a two-dimensional convolutional neural network is constructed.
3. The Keyboard keys are integrated with hand movements using the PyAutoGUI module. 
4. The Streamlit web framework is utilised to develop a user interface. 
5. Using streamlit.io sharing, a webpage with source files and a demo is published.
6. 







**Gestures obtained after Data collection and preprocessing**:
Palm, fist, thumbs up, thumbs down, index pointing right, index pointing left and no gesture (Left to right)

![alt text](https://github.com/gayathri1462/Controlling-Media-Player-with-Hand-Gestures-using-Convolutional-Neural-Network/blob/main/images/gestures.png?raw=true)

#### Architecture of trained CNN model: 
<img src="https://github.com/gayathri1462/Controlling-Media-Player-with-Hand-Gestures-using-Convolutional-Neural-Network/blob/main/images/CNNlayers.png?raw=true.type" width="300" height="300">



#### Performance Evalutaion:
<img src="https://github.com/gayathri1462/Controlling-Media-Player-with-Hand-Gestures-using-Convolutional-Neural-Network/blob/main/images/Confusion%20matrix.png?raw=true.type" width="400" height="400">


