# PCC
A tiny machine learning model for classifying parsley and coriander.

This project was created as part of our TinyML workshop delivered by KAUST Academy.

The project was built upon Edge Impulse and then deployed on Arduino's Nicla Vision through OpenMV.

# Provided files
The provided files here are:
1- `ei_image_classification.py` which is the python script ran in OpenMV and created automatically by Edge Impulse.
2- `trained.tflite` which contains the model in TensorFlow Lite framework.
3- `labels.txt` which contains the labels of the model (parsley and coriander).
4- `edge_impulse_firmware_arduino_nicla_vision.bin` which contains the firmware bootloader for OpenMV.

# User Manual
Here are step-by-step guide on how to use it.

## 1 Boot the bootloader in OpenMV
- Download `edge_impulse_firmware_arduino_nicla_vision.bin` and run in on OpenMV (Tools -> Run a bootloader -> select the file)

## 2 Move the required files to the Nicla Vision
- The files `trained_tflite` and `labels.txt` need to be in the Nicla Vision, so you must move them manually into the machine's storage through the file explorer.

## 3 Run the python script in OpenMV
- Simply, run the `ei_image_classification.py` script in OpenMV and it should be able to classify between parsley and coriander successfully :)
