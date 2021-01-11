# IOT-DEVICE-FOR-DISABLED-PEOPLE



#In this Project IoT device was developed which enhances communication between the physically disabled (Deaf, Dumb and Blind). The various functionalities performed by each module is as follows:
Hand Gesture Model: The flex sensor records the resistance obtained by performing the gestures. The value is then processed by the Arduino and the corresponding character is sent to the text to speech application which then generates the output.
 OCR Model: The camera captures the image placed in front of it and the image is processed by the raspberry pi using the OCR and the OpenCV libraries. The result is processed and sent to the text to speech for further processing of the output.
 Live Tracking Module: Whenever the alert switch is pressed, the GPS module activates, and the alert text message is generated and forwarded to the respective mobile number of the user. The output is further sent to the text to speech for generating an audio and visual.
