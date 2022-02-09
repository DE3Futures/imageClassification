cloned in python from: https://github.com/spmallick/learnopencv/tree/master/AgeGender

Requirements: 
- Download OpenCV from: https://opencv.org/releases/ then setup for Python in your environment.</br>

I tried followed the following tutorial: https://docs.opencv.org/4.x/d5/de5/tutorial_py_setup_in_windows.html, however, none of these methods worked for me. I am unsure why... when trying "import cv2" in a python shell there was an error that it could not find the package :// </br>

Instead, although "unofficial" this works in an anaconda environment: ```pip install opencv-python```. This also works in downloaded Python environment if I add the module's path to the system paths. You need to make sure the module has an empty ```__ini__.py``` inside.</br>

Going to try again following this guy's comments: https://answers.opencv.org/question/237756/at-my-wits-end-with-opencv-build-from-source-please-help/. 