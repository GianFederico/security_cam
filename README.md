# SIDE-security_cam
This is a simple secutiry cam that records video feed only when a face or a body is detected in the current frame.

As long as the progam has a video feed from the camera, it checks every frame in order to determine whether a face or a body is present or not.
If a face or a body is detected it starts recording until there are no faces or bodies in the frame, at which moment starts a countdown of 3 seconds and then, if still no faces or bodies are in the frame, it stops recording and saves the file with the exact date as file name.
(The countdown is necessary to avoid having a lot of very short videos)
