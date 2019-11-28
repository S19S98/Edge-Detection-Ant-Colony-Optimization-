# Edge-Detection-Ant-Colony-Optimization-
Using the ant colony optimization algorithm to find the edges in a picture.

ANT COLONY OPTIMIZATION:

Ant Colony Optimization (ACO) algorithm is an approach used to provide a solution to an optimization problem.
ACO follows the mechanism adapted by ants to search for optimal paths by performing combined activity of all ants in the colony.
Alberto Colorni, Vittorio Maniezzo and Marco Dorigo were the first to think of a calculation to reproduce the ants behavior.

Ants meander arbitrarily from their hives in search of food and water, when they find it, they need to go back to their hives.
On their way back they leave behind a synthetic volatile liquid called pheromone.
Alternate ants take after the ways with maximum pheromone quantity instead of meandering around.
This marvel of nature is implemented in the ACO algorithm in order to find optimized solutions to various problems.


EDGE DETECTION:

Edges are significant changes in the intensity of an image or are the discontinuities.
Edge detection is an important processing paradigm for image processing, machine learning and computer vision and has important role in feature detection and extraction.
Furthermore it finds its applications in:
  Recognizing textures
  Identifying tumors
  Detecting objects and details in images
  Finding land area of farm plots
  License plate identification
Some of the techniques used in image edge detection are:
  ACO
  Sobel Filter
  Canny Filter


EDGE DETCTION using ACO:

Numerous techniques are executed throughout the years for edge for edge detection among which utilizing Ant Colony Algorithm to distinguish the edge in a picture.
This is done with the help of ACO utilizing MATLAB.
It requires a picture as an input, converts it into a binary image of limited size
An iterative process detects the sharp changes in intensity of the image and marks them.
After complete traversing a resultant image is produced depicting the edges present in the picture.

the methodology followed considers the sharp intensity changes made in the picture for distinguishing the edge
MATLAB is chosen over other programming languages in the light of its simplicity and processing capability.
Image edge detection can be considered as a problem of identifying the pixels in an image, which relate to edges. 
A 2-D image can be represented as a two dimensional matrix in which each element is considered as the pixel.

the image is represented as a construction graph using an 8-connectivity pixel configuration
In an 8-connectivity configuration, each pixel is connected to every other pixel that touches one of its corners or edges. Ants move on the graph from one pixel to another pixel using these connections. An ant cannot move from its current pixel to a disconnected pixel. This means they can only visit the adjacent pixel.
Artificial ants traverse over the image and move from one pixel to another. The movement of the ants depends on variation in the intensity values of each the pixel. The aim of the ants’ movement is to construct a final pheromone matrix that represents the edge information. Each element in the pheromone matrix represents a pixel in the image. 


APPLICATIONS of EDGE DETECTION:

  Finding land area of farm plots.
  Detecting shaded regions of liver.
  License plate detection.
  Finger print recognition. (edge detection enhances the quality of the image and leads to improvement)
  Also prove helpful in self driving cars as they will better understand the white pigmented images over black rather than colored at     times.


COMPARSION among ACO, SOBEL and CANNY:

  Sobel and Canny filters are mostly used techniques in edge detections areas. But they are only taken into account for images with large gradient of color and brightness.
  Neither Sobel nor Canny can detect the shaded regions like in case of liver images. To suppress noise Canny filter smooths out the image, but this leads to loss of edge points. On the other hand Sobel in the first hand itself fails to detect the edges.
  The traditional methods including the Sobel and Canny filters are not only very complex in nature but at the same time are sensitive to noise, thus requires filtering which often removes edges of the image along with the unwanted noise.
  But the ACO comes in handy when the other techniques fail to produce the desired output as mentioned in the above two scenarios.  


