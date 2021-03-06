The list of images generated after pre-processing will be used to highlight relevant features in the images hence.
In a conventional FER system, the relevant features are facial features.

For the purpose of feature extraction we will be using Local Binary Patterns (LBP).

In LBP, we focus on 9 pixels (3x3) at a time.
We first compare the neighbouring pixels with the central pixel, and assign a value of '0' or '1' to the neighbouring pixel relative to the central pixel.
Doing so we get a set of 8 bits which we can convert into a byte, going either clockwise or anticlockwise.
Further we convert it into a decimal value which is assigned to the central pixel.
The same is done for each pixel of the image, hence, highlighting facial features like eyes,nose,eyebrows and mouth.

LIBRARIES USED -
1. numpy
2. matplotlib

WHAT WE INTEND TO DO -
1. After pre-processing of images, we have a list of 876 images on which we have to apply the LBP algorithm to extract their features.
2. We have created a simple function for LBP using basic functions.
3. We then run this algorithm on all images using loops, saving the ready images in a list.
4. Finally we plot histogram of each image and save them in a separate list.

FINAL RESULTS EXPECTED -
1. A list of images that have their features extracted.
2. A list of corresponding histograms of images.

REFERENCES -
1. www.geeksforgeeks.org
2. www.stackoverflow.com
