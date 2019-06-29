# 56_RoboHacker

Features Of BlindHelper Project 

1. Newspaper Reading
2. Face Recognition
3. Currency Note Detection
4. Tracking using android app
5. Sensing Band


# Newspaper Reading

In Newspaper Reading , Basically  we capture the image using raspberry pi camera  and the python code in pi extracts the words from the image and then the blind people can hear the words using speaker.


# Face Recognition

In face recognition , Python code will take the image of the person in front of the camera label as person 1 and train the model in the real scenarion and if the same person comes in the camera again and it will detect the face of that and we can train the model with specfic persons in the real scenario

# Currency Note Detection

In Currency Note Detection , we train the model with 7 classes as 10 , 20 ,50 , 100 , 200 , 500 , 2000. In each class we have approx 300 images and we train the model with this dataset and this gives the accuracy of about 95%.

# Tracking using android app

In this we use gps module with raspberry pi and the gps module takes the value of the latitude and longitude with date and time with it and upload to the fireabse realtimely and android app get the data from realtime database firebase and  shows in the google map activity can be used by  blind person's wellfisher to track the blind person 

# Sensing Band

The sensing band is basically a band that blind person can wear on his/her wrist. In it , we use  three ultrasonic as two ultra sonic for left and right and one is for up and  down which is mounted on server motor. This band tell the blind person where is open path by two servo motors on his left and right side of the sensing band.  
