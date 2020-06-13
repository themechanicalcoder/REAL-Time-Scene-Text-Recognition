# REAL-Time-Scene-Text-Recognition

It uses the camera to take the video and recognises the text within it.
For detecting the text I have used EAST Text detector and CRNN for Text Recognition.
The interesting part about the project is that it uses only OpenCV for and does not use any other Deep Learning framework like Tensorflow or Pytorch to run.
But how is that possible?
Well, I used trained EAST Text Detection and CRNN models (trained in Tensorflow and Pytorch respectively) and converted them to frozen graphs and ONNX models respectively so that they can be used directly by OpenCV.

A video describing this project can be found at [link](https://www.youtube.com/watch?v=5h_ReiBSlaM)
