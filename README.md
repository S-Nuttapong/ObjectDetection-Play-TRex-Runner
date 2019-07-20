# ObjectDetection-Play-TRex-Runner 



![DIno GIF](https://user-images.githubusercontent.com/52415315/61345304-b35be300-a87e-11e9-86ad-2b9a2eb613f3.gif)



## Introduction
This is only a part of my exploration of Object Detection. So far model can achieve 3560 points on average and 700 as the highest scores. The main challenge is computational power, model was able to run with 5 FPS with visualization as shown above, by turning off the visualization, model was able to retain a few more FPS, therefore model tend to do better on better computer. However, as the speed of the game increases and exceeds computer's capability, the model will not be able to capture the in coming obstacles and react in time. Hence Object detection may not be  efficient for this task and should not be considered as a good practice.

## Further thought
More promising solution is to take numerical data such as distance between obstacles, speed of the game, size of dinosaur and obstacles directly from game's source then one may consider using reinforment learning algorithm, instead of taking screenshot as image array and feed to object detection as this is less resource intensive and appear to be more suitable for this task.


## Requirements
- [Python 3.7](https://www.python.org/)
- [TensorFlow 1.14.0](https://www.tensorflow.org/)
- [OpenCV 4.1](http://opencv.org/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)
- [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

## Instruction
- Install the Object Detection API
- Download Trex_runner.zip and extract to Object Detection directory
- [Open Dinosaur game](http://www.trex-game.skipser.com/), bear in mind other soucres may give different result
- Run the TRex_runner.py

## Notes
- This project was done on macbook pro with 1280x800 resolution, to achieve the same or better result the parameter of screen  in TRex_Runner.py must be adjusted accordingly
