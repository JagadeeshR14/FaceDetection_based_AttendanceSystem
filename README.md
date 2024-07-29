# Face Detection based Attendance System

## ABSTRACT :

The proposal is mainly about the face detection-based attendance system which overcomes manual
method of taking attendance, reduces the time to take attendance and avoids proxy. Unlike other
Biometric attendance systems like fingerprint recognition, DNA matching, face recognition, Iris
recognition and voice recognition, this face detection-based attendance system does not require
any person to be in contact with the fingerprint reader module, which reduces a lot of time,
improves security levels and low fraud rate.

This project involves the student, faculty or employee attendance by face recognition. The face
detection and recognition were carried out by using ESP32 cam module which captures the images
of the available students in the classroom. Using this image, it recognizes and compares with the
images in the database and marks their attendance

Keywords: Face Recognition, Face Detection, ESP32 camera module.

## PROBLEM STATEMENT :

Current attendance management methods are laborious, error-prone, and lack accountability. 
Traditional biometric systems face limitations like physical contact requirements and proxy attendance issues. 
The challenge is to develop an automated attendance system using face detection and IoT technologies. 
This system should offer seamless, contactless attendance tracking, ensuring accuracy, security, 
and user convenience across diverse environments like educational institutions and corporate settings.

## HARDWARE REQUIRED :

1. ESP32 Camera Module
2. Arduino Uno
3. Connecting Wires
4. USB - Power Cord
5. Memory Card or Storage Card

## SENSOR MECHANISM :

The primary sensor used in this system is the camera integrated into the ESP32-CAM module (OV2640). 
This camera captures images of individuals in the classroom or designated area. 
The captured images are then processed using face detection and recognition algorithms to identify individuals and mark their attendance. 
These algorithms analyze facial features, such as contours and key points, to compare them with images stored in the database. 
Upon successful recognition, attendance is recorded either locally or on a remote server, depending on the system configuration.

## CONNECTIONS AND DIAGRAMS :

<img width="461" alt="image" src="https://github.com/user-attachments/assets/976f996e-eea5-49f3-9a7a-865709dc3bbd">

There are the other Diagrams like Block diagram and more. Click [here](Diagram) to explore.

## RESULT :
![Camera Feature](https://github.com/user-attachments/assets/04a62761-386d-48ce-b296-7a360b048ead)

Click [here](Result) to explore all the screenshot Results/Outputs of the Project.

## CONCLUSION :

Different classrooms may have different lighting, seating layouts, and atmosphere. There may also  be students with diverse facial expressions, hair styles, beards, spectacles, and so on. This approach can be adopted to improve the management of attendance and leaves. The system will save time, reduce the amount of work that the administration needs to do, replace stationery with electronic equipment, and minimize the quantity of human resource required for the purpose.
