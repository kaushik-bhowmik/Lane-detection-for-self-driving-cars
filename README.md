# Lane-detection-for-self-driving-cars
This project, I worked on lane detection for self-driving cars.
The pipeline for project is :
1. Defining the preprocessing functions for the images which include converting the image into gray-scale and then performing Canny edge detection.
2. As the camera's field of view is large, cropping the image to just include the region of interest. 
3. Utilizing the output from region of interest and performing an Hough transform on the image.
4. Drawing the line on the output of Hough transform, which are lanes of road.
In this way, the lane detection for self-driving car can be done by using computer vision techniques.
