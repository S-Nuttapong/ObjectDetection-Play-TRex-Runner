# ObjectDetection-Play-TRex-Runner 



![GIF](Dino GIF.gif)


## Introduction
This is only a part of my exploration with Object Detection and should not be considered as a good practice. So far model can achieve 400 points on average and 700 as the highest scores. The main challenges was computational power, model was able to run with 5 FPS with visualization as shown above, by turning off the visualization, model was able to retain a few more FPS, therefore model tend to do better on better computer. However, as the speed of the game increases and exceeds computer's capability, the model will not be able to capture the in coming obstacles and react in time. Hence Object detection maybe not the not efficient for this task.

## Further thought
Better solution is to take numerical data such as distance between obstacles, speed of the game, size of dinosaur and obstacles directly from game's source then one may consider using reinforment learning algorithm, instead of taking screenshot as image array and feed to object detection model.  


## Requirements
- [Python 3.7](https://www.python.org/)
- [TensorFlow 1.14.0](https://www.tensorflow.org/)
- [OpenCV 4.1](http://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)

## Technologies Used
- [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)


## Notes
- This project was done on macbook pro with 1280x800 resolution, to achieve the same or better result the variable in TRex_Runner.py must be adjusted accordingly
