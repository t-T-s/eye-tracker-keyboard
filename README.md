# eye-tracker-keyboard

Implementations of a keyboard which can be partially controlled using eye movements using python.

It takes the feed from the webcam and finds the locations of the eyes. After localizing the eyes, the cornea is identified from thresholding. White pixels are counted and the side of the keyboard is decided likewise. Then a blink is used to type a letter. 

Practically the performance is highly sensitive to how lit the room is.

### Dependencies:
You can download the model file (*shape_predictor_68_face_landmarks.dat*) for dlib from this link: http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
