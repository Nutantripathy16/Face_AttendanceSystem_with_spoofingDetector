# Face Attendance System with Anti Spoof Detector
 This repository will contain my projects related to Face attendance system using face recognition with Python!

## About

A basic interface is built using tkinter which will be working as an attendance system. 
openCv and Face recognition library are used for videos processing and face recognition stuffs. Moreover, Anti Spoofing is done using pre built model and details are in the Silent_Face_Anti_Spoofing folder 

## Usage
We need to run the main.py file in face-attendance-system to get to the following result<br><br>
So, the above mentioned python script will provide us with an interface or application which will validate some face recognition use cases, there are major three functions on the opening page of the application. These are:-
<br>
* Login :- Used as a login for already registered users
* Logout :- Used for logging out for already existing users
* Register new user :- Used to register new and unknown faces
</p>
So user needs to start by registering new faces for unknown people using register new user. So application will save the name and encodings related to the unknown face in database (db)
<br><br>
Now if known faces come in front of camera then app will allow for login and logout by recognizing face
<br><br>
If unknow face comes, user will get the notification of "Unknown user detected"
<br><br>
If someone will try to spoof the system using some picture of someone else then user will get alert warning that spoofing is detected
<br><br>
Block person detection is also part of this application
