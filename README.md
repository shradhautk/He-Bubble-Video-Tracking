# He-Bubble-Video-Tracking
 This project utilizes advanced computer vision techniques, including Mask R-CNN, to accurately identify and monitor helium-induced bubbles in videos of  irradiated PdNi samples obtained from TEM. Researchers and developers can leverage this resource to enhance material characterization under extreme conditions, ensuring safety and reliability in nuclear environments.

The code includes several key steps:

Importing necessary Python modules and libraries for image processing, machine learning, and visualization.

Downloading images and a pre-trained Mask R-CNN model from Google Drive.

Loading image frames and displaying a sample image.

Defining functions for the Mask R-CNN model and prediction.

Performing bubble detection on image frames using a sliding window approach. The code locates and evaluates He bubbles in each frame, considering factors like the size of the bubble and its position within the frame.

Tracking the detected bubbles across multiple frames and analyzing their trajectories.

Drawing bounding boxes and labels around the tracked bubbles in the images.

Converting the tracked bubbles into a video, creating a visual representation of their movement across frames.

The code is designed for analyzing He bubbles in transmission electron microscopy (TEM) micrographs of ion-irradiated iron-chromium steel. It uses the Mask R-CNN model to segment and track these bubbles, providing valuable insights into their behavior and movement over time.

Here is the link to tracking of bubbles in video: https://drive.google.com/file/d/1DUdMRt0g9iLTcWlaM2XkHAX1x_V8wkD8/view, https://youtube.com/shorts/hTLPorkpK7k?feature=share
[![Video](https://github.com/shradhautk/He-Bubble-Video-Tracking/assets/101154495/ad8f25f6-2207-47b3-be4c-0e4ab30927f9)](https://youtube.com/shorts/hTLPorkpK7k?feature=share)


<video width="320" height="240" controls autoplay>
    <source src="https://youtube.com/shorts/hTLPorkpK7k?feature=share" type="video/mp4">
    Your browser does not support the video tag.
</video>
