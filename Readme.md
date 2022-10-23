# EyeAI   <img src="Images/logo_final.png" alt="Logo" width="100" height="70" />

AIM -  Training, deploying deep learning models for ophthalmology diagnosis on android app

[![Get it on Google Play](https://lisk.io/sites/default/files/pictures/2020-01/download_on_the_play_store_badge.svg)](https://play.google.com/store/apps/details?id=com.amritpal.eyeai)


## Goals - 
- [x] Train models
- [x] Test models
- [x] Android app framework to deploy model
- [x] On device model prediction
- [x] Capture image / Upload image from device
- [x] Image testing before prediction(Is it a Retina image or not?)
- [x] Report False predictions by model
- [ ] Add "Share AI's Report" button
    - [x] Without images 
    - [ ] With images 
- [x] Suggestions to improve app button 
- [ ] Prediction probabilities
- [ ] Choosing model function - Multiple models for different diseases
- [ ] Annonymization of files before sending to model
- [ ] Image augmentation before making prediction


Frameworks used - 
- Model training - Tensorflow lite
- Android deployment - Kotlin and Android Studio


App size - 20 mb 
Coverage of Android devices - more than 98% 


## Screenshots
| Normal                  |  Diabetic retinopathy | Maculopathy | Retinitis pigmentosa |
| :---:                     |     :---:      |          :---: |          :---: |
| <img src="Images/Correct_diagnosis003.jpg" alt="Normal" height=350/> | <img src="Images/Correct_diagnosis002.jpg" alt="Maculopathy" height=350/>   |   <img src="Images/Correct_diagnosis001.jpg" alt="Diabetic retinopathy" height=350 />  |   <img src="Images/Correct_diagnosis004.jpg" alt="Retinitis pigmentosa" height=350 />  |


## False image type prediction
| CT scans                   |  Xrays | Random faces | Screenshots |
| :---:                     |     :---:      |          :---: |          :---: |
| <img src="Images/False_prediction_detection003.jpg" alt="CT_scan" height=350/> | <img src="Images/False_prediction_xray.jpg" alt="Xrays" height=350/>   |   <img src="Images/False_prediction_detection006.jpg" alt="Random faces" height=350 />  |   <img src="Images/False_prediction_detection003.jpg" alt="Screenshots" height=350 />  |


## Training
| Training loss   |  Training accuracy | Confusion matrix |
| :---:                     |     :---:      |          :---: |  
| <img src="Images/loss.png" alt="Training loss" height=350/> | <img src="Images/accuracy.png" alt="Training accuracy" height=350/>   |   <img src="Images/cm.png" alt="Confusion matrix" height=350 />  |  


### Maybe sometime in future
- [ ] Uploading folder of images at once
- [ ] Cloud based interpretation on bigger/better models
- [ ] Links to model training process and accuracy statistics
- [ ] GradCam/Explainable AI components

