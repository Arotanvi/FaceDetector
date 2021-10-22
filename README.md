# FaceDetector
Problem Statement - to detect the face from a image and to show a rectngle around facial part of image
Library used - opencv
Steps being followed:-
1.To use cascade classifier to store the features/info of a face
2. To read the image using cv2.imread() method
3. To convert the image into gray image via cv2.cvtColor method
4. Detect the face from gray image via detectMultiScale method
5. to make a rectangle around the face of image
6. resize the image obtained in step 5
7. show it in a window using imshow() method and use destroyAllWindows() to close that window.

=> Image date obtained from detectMultiScale method is a numpy matrix 
