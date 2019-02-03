# Real-Time-Face-Recognition
This application recognises people through video stream based on face data collected 

Data is collected first using OpenCV library and using haarcascades classifier which is used to identify a face in the video stream using a combination of matrices. Using this , the data of face is collected and stored.

Next , when a video stream is turned on , The data about faces is loaded in an array and a corresponding label using classID is generated. This accounts for our training dataset.
The testing data point is the face that is captured through video stream currently. It is then classified using KNN algorithm to display the name of person in the video stream.

