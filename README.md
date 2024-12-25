# Eye-as-cursor
The camera detect your eyes and your eyes act as cursor. Blink of your eye make a click. Moving your head or eye will move the cursor according to your wish.

# Functioning 
First we need to open the webcam, to do this we use cv2 module. After that our objective is to detect the face in the frame (whether the face is visible in the video captured by cv2). For this we use mediapipe to detect face and then we assign the eye position number to the landmark (mediapipe). Lastly we use PyAutoGui to match the eye movement with cursor.
