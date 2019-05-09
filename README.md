[//]: # (Image Reference)

[image1]: ./readme_images/images.PNG "Images"
[image2]: ./readme_images/video.PNG "Videos"

# Video Artistic Style Transfer With Pytorch
Transfer the style from one or more images (for example, a painting) to a whole video using Pytorch. 
Developed as a capstone project for [Harvard CS50: Introduction to Computer Science](https://online-learning.harvard.edu/course/cs50-introduction-computer-science).

[Watch the video with the implementation and final result](https://www.youtube.com/watch?v=jqcolu3l644)

![Images][image1]
![Videos][image2]

## Dependencies:
1. OpenCV 3
2. PyTorch 1.0
3. Matplotlib
4. Numpy
5. PIL

## Steps to run:
1. Install all the dependencies on your computer. (Use Anaconda preferably to install all the necessary libraries and packages)
2. Open Anaconda Command Prompt
3. Change directory (cd) to the location where the python file is present (here, "Video Artistic Style Transfer.py")
4. Make sure to put the input style images into the directory: "input_style_frames" and name the style images as "style_1.jpg", "style_2.jpg", and so on. If you are using a different directory, you may need to change the folder names in the code.
5. Enter the following command in the Anaconda Terminal: python "python-file.py" "path-to-input-video"
  For Ex: python "style transfer on video.py" input_video\sample_video.mp4
6. The program will run successfully and you will see the desired output processed video in the folder: "output_processed_video".
7. Open the video and check the result.

## Video Credits:
Link : https://www.youtube.com/watch?v=rUWxSEwctFU
