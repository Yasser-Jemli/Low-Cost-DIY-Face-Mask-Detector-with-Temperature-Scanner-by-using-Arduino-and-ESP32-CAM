
# Face Mask Detector with Temperature Scanner by using Arduino and ESP32-CAM

                                under construction 

Face Mask Detector with Temperature Sensor Kit. In this kit, user need to scan their body temperature first before can scan their face mask. We are using MLX90614 Temperature Sensor for this project because it using infrared to read temperature which is suitable for this project than any other temperature sensor. It sense temperature contactless rather than need a contact to read temperature. In this project, your body temperature should be between 33 - 39 degree celcius to pass the scan. other than that, it shown error. 

after passed the temperature scan, you need to scan your face. You need to stand between 35-60cm from the camera to scan your face. if not, the the camera will not scan your face and ask you to come closer or take a step back. You need to pass the threshold value, which is 80% of your face covered to pass the scan. There is also a pushbutton to open the door manually from inside.
