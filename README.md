# PCC: Parsley and Coriander Classifier
A tiny machine learning model for classifying parsley and coriander.

This project was created as part of our TinyML workshop delivered by KAUST Academy.

The project was built upon Edge Impulse and then deployed on Arduino's Nicla Vision through OpenMV.

# Provided files
The provided files are all included within the zip files attached up there (`ei-parsley-vs-coriander-arduino.zip`)


# User Manual
Here are step-by-step guide on how to use it.

## 1 Reset the Nicla Vision
- This step isn't sequential but it's better to reset before working
  
## 2 Upload the zip file into Arduino IDE
- Simply by going to Sketch -> Include Library -> Add .ZIP Library and then select `ei-parsley-vs-coriander-arduino.zip`.

## 3 Choose the uploaded file with the desired machine
- Go to Files -> Examples -> parsley_vs_coriander_inferencing -> nicla_vison -> nicla_vision_camera and the script should open in front of you
  
## 4 Verify and upload the sketch into the machine
- You can do so from Arduino IDE's UI.

## 5 Go to Serial Monitor (top left of the IDE's UI) and start classifying!
- in Serial Monitor, you should be able to see the model's output being updated every 2 seconds (that's the default but you can change it however you want)

# And there you have it! 
