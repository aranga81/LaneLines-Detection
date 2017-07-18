# LaneLines-Detection
Python Pipeline to detect and draw the lane lines 

The goals / Steps of this Pipeline:
- Code that finds Lane lines on the road
- Test and validate the pipeline on Test Images & Videos

BRIEF OVERVIEW OF THE PIPELINE:

The process involves the following 5 steps:

1.) Converting the images / frames to grayscale

2.) Applying a Gaussian mask to filter any noise from the gray scaled image

3.) Use a Canny edge Detection function with threshold limits to detect spikes in gradient across pixels

4.) Select the region of interest and apply the mask to specify the lane limits

5.) Apply Hough Transform logic to determine the lines qualified as lane lines in each frame.

Read the project_writeup for complete description of the pipeline. Jupyter notebook P1.ipynb included in the repo. 
