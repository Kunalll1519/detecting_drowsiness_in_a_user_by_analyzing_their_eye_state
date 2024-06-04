Import a basic libraries of python.
Load the face and eye cascade classifiers
Load your trained model
Open the camera
Convert the frame to grayscale for face and eye detection
Detect faces in the frame
Extract the region of interest (ROI) for eyes
Resize the eye image to match the input size of the model
Normalize pixel values to be between 0 and 1
Reshape the image for model prediction
Predict drowsiness using the trained model
Determine the eye state based on the prediction
Draw rectangles around eyes
Display eye status text
Display the resulting frame
Break the loop if 'q' is pressed
Release the camera and close all OpenCV windows
