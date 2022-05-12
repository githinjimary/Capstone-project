# CAPSTONE-PROJECT
***BACKGROUND***
Most schools, especially day schools, face the challenge of students skiving lessons. Once they have been registered present in the morning, they escape school. Should anything bad happen to such a student outside school while the record states that the student was present in school, could reflect badly on the teacher. Therefore, as a day school teacher I chose this project to help reduce or manage this problem. The project involves creating a face detection APP that automatically detects students present in class and automatically records the attendance. The data is taken live by using a camera in class and can be done at any time of the day as many times as possible. 

***WORKING***
The project involves train a face recognition model that detects faces of students and registers their attendance in a csv file. Students from one class will be registered in the system by scanning their faces and registers them as present or absent.This information is saved as a csv file and sent to the respective classteachers through mail,the data is then stored in a database. 
This project can later be used to scan students in an entire school and send messages to the respective class teachers and parents when their student was absent.

****FACIAL RECOGNITION****
A facial recognition system is a technology capable of matching a human face from a digital image or a video frame against a database of faces, typically employed to authenticate users through ID verification services, works by pinpointing and measuring facial features from a given image.(according to wikipedia).It is built using dlib’s state-of-the-art face recognition, built with deep learning. The model has an accuracy of 99.38% on the
Labeled Faces in the Wild benchmark.
**how it works**
when one gives a picture of a user to record his/her "facial identity".
A first model will dig up whether there is a face or not and determine its location on the photo.
A second model will calculate the facial parameters. (distance between the eyes, shape of the chin,…)
Then save this "encoded" data by linking them to a name so that they can be compared with a future picture.
Then one gives a new nameless photo or live video and the same process will be repeated except that this time, a third model will compare the parameters of the face with those it already knows.

# GUI
***tkinter***
We used tkinter to deploy the project.Tkinter is a Python binding to the Tk GUI toolkit.

![Screenshot from 2022-05-10 12-07-24](https://user-images.githubusercontent.com/97385199/167604896-e78329da-bbce-4f9a-bade-39dde2f5a9d0.png)

A real time attendance was taken on thursday 5th of May and it worked well.

***OBJECTIVES***
    • To monitor the lesson attendance of students in class.
    • This automatically reduces the number of students skiving lessons and leaving school without permission. 
    • To enhance discipline through constant monitoring. 

***CHALLENGES***
    •Illumination: It changes the face appearance drastically, it is observed that the slight changes in lighting conditions cause a significant impact on its results.
    • Pose: Facial Recognition systems are highly sensitive to the pose, Which may result in faulty recognition or no recognition if the database is only trained on frontal face view.
    • Facial Expressions: Different expressions of the same individual are another significant factor that needs to be taken into account. Modern Recognizers can easily deal with it though.
    • Low Resolution: Training of recognizer must be done on a good resolution picture, otherwise the model will fail to extract features.
    • Aging: With increasing age, the human face features shape, lines, texture changes which are yet another challenge. 
    
 ***CONCLUSION***
Facial attendance has proven to have more advantages especially in maintaining discipline in a school than any other form of monitoring attendance. This project can also be used to monitor attendance of teachers or genereal workers.

 
 
 
