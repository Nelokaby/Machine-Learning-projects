# Machine-Learning-projects

## firstly, the model:
### 1- preparing data for model training ( we used MediaPipe and CV2 libraries for extracting points and for face detection from pictures).
### 2- splited the data to training, validation and testing.
### 3- used XGBoost regressor (based on decision trees models) 3 times for 3 positions.
### 4- we choose every time a random pic to validate the model.

## after training and validation:
### 1- we have read the video and converting it to frames. 
### 2- for each frame, we extracted the points and predicted the 3 position axis (pitch,yaw,roll) and drew it on each frame.
### 3- finaly, we converted the frames to video again.


# important reference : 
#### https://google.github.io/mediapipe/solutions/face_mesh.html
#### http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip
