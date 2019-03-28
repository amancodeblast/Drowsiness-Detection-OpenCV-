# Drowsiness Detection System in Windows

## Dependencies required to run the script

* Python installed
* Numpy installed 
* OpenCV installed 
* dlib installed
* imutils installed
* playsound installed
* agrparse insalled

## How to run the script

Download the [repo](<https://github.com/amancodeblast/Drowsiness-Detection-OpenCV->) to your workspace and navigate to the directory using command prompt and write the command 

'python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav'

and ...hit enter.

## How in the name of God does this thing works

Well lets first discuss the basic thing we are doing in this program, we are measuring the EAR(Eye Aspect Ratio) and if it falls below a certain value for a certain amount of time ...well then the driver needs to be reminded to be attentive ..using an alarm. The value mentioned above needs to be tuned taking various factors into consideration such as time of the day, lighting conditions and many more. 

 

