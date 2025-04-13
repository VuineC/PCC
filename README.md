# PCC: Parsley and Coriander Classifier
A tiny machine learning model for classifying parsley and coriander.

This project was created as part of our TinyML workshop delivered by KAUST Academy.

The project was built upon Edge Impulse and then deployed on Arduino's Nicla Vision through OpenMV.

# Provided files
The provided files are all included within the zip files attached up there (`ei-parsley-vs-coriander-arduino.zip`)


# User Manual
Here are step-by-step guide on how to use it.

## 1 Upload the zip file into Arduino IDE
- Simply by going to Sketch -> Include Library -> Add .ZIP Library and then select `ei-parsley-vs-coriander-arduino.zip`.

## 2 Reset the Nicla Vision
- This step doesn't have to be after the upload but just in case the machine had other files within.
  
## 3 Verify and upload the sketch into the machine
- You can do so from Arduino IDE's UI.

## 4 Go to Serial Monitor (top left of the IDE's UI) and start classifying!
- in Serial Monitor, you should be able to see the model's output being updated every 2 seconds (that's the default but you can change it however you want)

# And there you have it! 
