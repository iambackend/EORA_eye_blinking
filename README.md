# EORA_eye_blinking
EORA Test Task with eyes blinking
## How to run
0) Clone this repo.

1) `pip install -r requirements.txt`

2) `python detect_blinks --shape_predictor shape_predictor_68_face_landmarks.dat` – if you want to work with webcam.
   
   `python detect_blinks --shape_predictor shape_predictor_68_face_landmarks.dat --video VIDEOFILE` – if you want it with video.

EYE_AR_THRESH constant is not always optimal, maybe you will need to modify it. Choose between 20 and 30. I suppose it depends on lightning, but not sure.

Press Q to quit.