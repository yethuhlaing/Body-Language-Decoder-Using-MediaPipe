# Body-Language-Decoder-Using-MediaPipe

This project is about how to leverage Mediapipe to estimate both facial and body landmarks. 
With that data custom pose classification models can be built to decode what a person might be saying with their body language with fine grain accuracy.

# Project Demo


https://user-images.githubusercontent.com/112906488/221361688-61f9489c-ad7e-453b-8977-4a5bcca56d51.mp4


# Workflow

- Installing Mediapipe and Dependencies
- Capture Landmarks using OpenCV and CSV
- Load Pose and Face Data using Pandas
- Train Sciki-Learn Pose Classification Model
- Evaluate Classification Model and Pickle
- Making Detections using the Model
- Decoded Body Language Demo
- Displaying Probabilities

# Pose Landmark Model

The landmark model in MediaPipe Pose predicts the location of 33 pose landmarks 

![image](https://user-images.githubusercontent.com/112906488/221356587-c5cc9c8d-a2ed-496d-974a-933c28339aab.png)
# Dataset

The following csv file stores the landmark coordinates of each face expression.

![image](https://user-images.githubusercontent.com/112906488/221356652-30c6d4b1-c045-4786-9501-2983726a9ee7.png)


