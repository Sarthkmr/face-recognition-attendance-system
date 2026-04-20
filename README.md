PROJECT TITLE: "Face Recognition & Attendance System"

This project is an automated attendance system that uses facial recognition technology
to make attendance tracking easier and faster. 

It is built using the Python programming
language and relies on several powerful libraries like face_recognition for recognizing faces,
OpenCV for capturing and processing video, Pandas for managing attendance data, and
smtplib for sending email notifications. 

The system is designed to work in real-time and is 
fully automated, making it a convenient tool for schools or colleges.The system works by
first loading a list of known students' faces and their names from a configuration file
(config.json). 

It then uses a webcam to capture video and detects faces in the video stream.
If a recognized face matches one of the known students, the system marks them as "Present"
and records the time, If a student is not recognized or not seen during the session, they are
marked as "Absent." 

All this data is saved in an Excel file with the current date and time
period (e.g., morning or afternoon).Once the attendance session is over, the system
automatically sends the Excel file as an email attachment to a designated teacher or
administrator. 

Additionally, if the session is in the morning, the system sends emails to the
parents of students who were absent, informing them about their child's absencel. This
ensures that parents are kept in the loop.The project is designed to be simple, efficient, and
easy to use. 

It eliminates the need for manual attendance tracking, reduces errors, and saves
time. The use of Python and popular libraries makes it flexible and easy to modify for
future improvements. Overall, this system provides a contactless, accurate, and automated
solution for managing attendance in educational institutions.
