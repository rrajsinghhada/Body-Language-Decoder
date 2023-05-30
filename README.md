# Body-Language-Decoder
<img src="./Decoder_in_action.gif" width="338">
## Overview
* developed a powerful implementation of MediaPipe, enabling accurate decoding of facial expressions to determine whether a person is happy or sad. 
* utilised the combined power of MediaPipe and OpenCV to capture facial and hand landmarks during specific actions. These landmarks were then exported into CSV format, serving as valuable input for training the MediaPipe model.
# Additionally, the system is capable of recognising and interpreting various hand gestures, including iconic gestures like "Wakanda forever" and "victorious."
* I trained and compared multiple machine learning classification models, including Logistic Regression, RidgeClassifier, RandomForestClassifier, and GradientBoostingClassifier. After evaluating their performance, logistic regression emerged as the top-performing model. I saved this model as a pickle file for future use.	 	 	 		
* Skills utilised: Mediapipe, Opencv	, Pikel, Logistic Regression, RidgeClassifier, RandomForestClassifier, and GradientBoostingClassifier
## dependencies
* python3.7-3.10
* python 3.9(recommended)
* Mediapipe
* cv2(for live detection)

Tested on macos(with m1 chips) and windows

### pip packages
`pip install -r requirements.txt` 

## Problems generally faced
1. mediapipe not found -> `pip install mediapipe` .
2. macos won't be able to install pywin module ignore this it wont affect the model.
3. If any other module not found `pip install 'name of the module'`
