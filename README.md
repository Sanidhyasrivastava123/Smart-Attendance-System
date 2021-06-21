# Smart-Attendance-System
It is a utility application for marking attendance by **Face Detection and Recognition** by live video-stream of students entering their classroom and generate the list of students attending the class. 

Smart Attendance System is the way to modernized the existing method of marking attendance on register. It helps to reduce complexity of management. Smart Attendance System not only provide record of attendance of student, it uses Machine Learning technique to identify person facial details to mark attendance on database and it can also perform statistical analysis of student data and provide recommendation to student. It is smart because it provide attendance record to student, teacher and admin in digitalize ways.

# Libraries Used:
**○ Numpy** - could be a library for Python, adding support for multi-dimensional arrays and matrices, in conjunction with an enormous assortment of high-level mathematical functions to operate on these arrays.

**○ Pandas** - is a fast, powerful, flexible, and easy to use open-source data analysis and manipulation tool, built on top of the Python programming language.

**○ Haar Cascade** - is a machine learning object detection algorithm used to identify objects in an image or video and based on the concept of features proposed by Paul Viola and Michael Jones in their paper "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.

**○ Datetime** - It’s a combination of date and time along with the attributes year, month, day, hour, minute, second, microsecond, and info.

**○ Face_Recognition** - Recognize and manipulate faces from Python or the command line with the world’s simplest face recognition library.

**○ OpenCV**  - a library of programming functions primarily geared toward real-time computer vision.

# Brief Overview

In this project attendance is recorded by face recognition using haar cascade files. Training of data is done by capturing the face photos of every student. An id is provided to every student. When the attendance is marked using this utility application, the photo is matched with the photos in training data and the attendance is marked  in the csv file.

# Code

The entire code is divided into four parts:
1. enter_date_column
2. Capture & Insert_new_entry
3. Train_data
4. Take_attendence_by_Detection




