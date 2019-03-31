# Drowsiness Detection System in Windows

## Dependencies required to run the script

* Python installed
* Numpy installed 
* [OpenCV installed](<https://www.learnopencv.com/install-opencv3-on-windows/>)
* [dlib installed](<https://www.learnopencv.com/install-dlib-on-windows/>)
* imutils installed
* playsound installed
* agrparse insalled

## How to run the script

Download the [repo](<https://github.com/amancodeblast/Drowsiness-Detection-OpenCV->) to your workspace and navigate to the directory using command prompt and write the command 

'python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav'

and ...hit enter.

## How in the name of God does this thing works

Well lets first discuss the basic thing we are doing in this program, we are measuring the EAR(Eye Aspect Ratio) and if it falls below a certain value for a certain amount of time ...well then the driver needs to be reminded to be attentive ..using an alarm. The value mentioned above needs to be tuned taking various factors into consideration such as time of the day, lighting conditions and many more. 

 

## Coding Stuff

#### Argument while executing the program



* **--shape-predictor** : This is the path to dlib’s pre-trained facial landmark detector ( is included in the repository)                                                                                                                                                                   

* **--alarm** : Here you can optionally specify the path to an input audio file to be used as an alarm.

* **--webcam** :  This integer controls the index of your built-in webcam/USB camera.

  

  #### The parameters

  **Eye Aspect Ratio** threshold has its value near 0.3 and the no. of consecutive frames after which the alarm is blown are kept 45-50

  

