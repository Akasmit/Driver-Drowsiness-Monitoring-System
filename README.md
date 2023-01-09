
# Driver Drowiseness Monitoring System




## About
The Project showcases the System, wherein the driver alertness is monitored. It's soul purpose is to alert the driver when signs of the drowisiness or distractionn are detected.
The system comprises of three mode detection.


## Working

This is how it works:  
while the driver is driving the vehicle, the facial expressions are taken in consideration.  
If the driver is in active state the system will detect as an active state.  
If the driver is tired for feeling drowsy it will be detected as a drowsy state.  
If the driver gets into sleep it will be detected as a sleeping state.  



    
## Dependencies
dlib  
cv2  
numpy  


  
Compatible with: Any PC or laptop with Python installed on Chrome, Safari, Opera and Edge. (Just modify the code accordingly)
## Screenshots

![App Screenshot](https://www.linkpicture.com/q/Screenshot-2023-01-06-at-11.38.18-PM_2.png)

![App Screenshot](https://www.linkpicture.com/q/Screenshot-2023-01-06-at-11.38.02-PM.png)


## Usage

### Detect Face and Eyes in a Single Image  
Put your file to be detected in images folder with name test.jpeg or change the file path in to your image file.
Run script using:

python face_and_eye_detector_single_image.py     

### Detect Face and Eyes in a Webcam Feed
Run script using:

python face_and_eye_detector_webcam_video.py  

### Drowsiness Detection
Run script using:

python drowsiness_detect.py
The algorithm for Eye Aspect Ratio was taken from pyimagesearch.com blog, by Adrian RoseBrock.
