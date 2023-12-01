# Digital-Image-Processing-Lab-SRM-University-
This Repository Contains a Set of Questions of Digital Image Processing Lab Experiments of SRM(AP) University
LIST OF PRACTICAL EXPERIMENTS
1. Perform the following operations using library functions
a. Read, Display and write any color image in other formats.
b. Find RED, GREEN and BLUE plane of the color image.
c. Convert color image into gray scale image and binary image.
d. Resize the image by one half and one quarter.
e. Image rotates by 45, 90 and 180 degrees.
2. Create black and white images (A) of size 1024x1024. Which consists of alternative horizontal lines of black and white? Each line is of size 128.
Create black and white images (B) of size 1024x1024. Which consists of alternative vertical lines of black and white? Each line is of size128.Perform the following operations on Image A and Image B.
a. Image addition of A and B
b. Subtraction of A and B
c. Multiplying Images of A and B
a. Create a grayscale image of size 256x1024. Intensity of image should vary sinusoidal.
b. Create a white image of size 256x256, with black box of size 58x58 at centre.
3. Develop programs for following intensity transformation operation on a gray scale image. Collect any gray scale image from any source. Process that image using these operations.
a. Image negative
b. Log transformation and inverse log transform: s = c log (1+r), c is a const, r ≥ 0. s is pixel intensity of output image, r is the pixel intensity of input image. Study the effect of constant c on the quality of output image.
c. Power law transformation: Study the effect of different values of Gamma used in this transformation.
d. Contrast stretching
e. Gray level slicing
4. Develop programs for following spatial filtering operations on a gray scale image.
a. Averaging: Implement averaging filtering operations for different window sizes and study their effect on the quality of output image. Write your observations on output image quality.
b. Weighted averaging: Implement weighted averaging filtering operations for different window sizes and study their effect on the quality of output image. Write your observations on output image quality.
c. Median filtering: Implement weighted averaging filtering operations for different window sizes and study their effect on the quality of output image. Write your observations on output image quality.
d. Max filtering
e. Min filtering
5. Take a gray scale image and add salt and pepper noise. Write programs for following operations and observe their outputs
a. Linear smoothing or Image averaging
b. Weighted averaging
c. Median filtering. Compare the output quality among Image averaging and median filtering.
d. Max filtering
e. Min filtering
6. Write programs to perform following sharpening operations on a gray scale image
a. Laplacian filter
b. Filtering using composite mask
c. Unsharp masking
d. High boost filtering
e. Filtering using first order derivative operators such as sobel and prewitt mask.
7. Write a program to improve contrast of an image using histogram equalization. The prototype of the function is as below:
histogram_equalisation(input_Image, no_of_bins);
The function should return the enhanced image. Consider two low contrast input images. Study the nature of the output image quality in each case by varying the number of bins.
8. Take a low contrast gray scale image (A) and a high contrast gray scale image (B). Write a program to improve the contrast of A with the help of image B using histogram specification or matching. The prototype of the function is as below:
Histogram_sp(input_Image, specified_Iage, no_of_bins);
The function should return the enhanced image.
9. Develop programs to implement frequency domain smoothing filters (Ideal, Butterworth and Gaussian) and apply these filters on a gray scale image.
a. Compare/comment on the output of Ideal, Butterworth and Gaussian Low pass Filters having the same radii (cutoff frequency) value.
b. Consider a suitable gray scale image and demonstrate the ringing effect on the output of Ideal low pass frequency domain filter.
c. Compare the output of Butterworth low pass filters (order n=2) for different cut-off frequencies (5, 15, 30, 90, 120).
d. Compare the output of Gaussian low pass filters for different cut-off frequencies (5, 15, 30, 90, and 120).
10. Develop programs to implement frequency domain sharpening/High pass filters (Ideal, Butterworth and Gaussian) and apply these filters on a gray scale image.
a. Compare/comment on the output of Ideal, Butterworth and Gaussian High pass Filters having the same radii (cutoff frequency) value.
b. Consider a suitable gray scale image and demonstrate the ringing effect on the output of Ideal high pass frequency domain filter.
c. Compare the output of Butterworth high pass filters (order n=2) for different cut-off frequencies (5, 15, 30, 90, 120).
d. Compare the output of Gaussian high pass filters for different cut-off frequencies (5, 15, 30, 90, and 120).
11. Develop program to add different types of noise in a gray scale image and write functions to implement following filters for image restoration in presence of these noises.
a. Remove Salt and Pepper Noise
b. Minimize Gaussian noise
c. Median filter and Weiner filter
12. Write and execute program for image morphological operations erosion and dilation.
13. Implement Morphological smoothing using opening and closing
14. Develop program to implement point and line detection masks. Detect points and lines using these masks for a given gray scale image.
15. Develop programs for edge detection using different edge detection mask.
16. Develop programs to achieve image segmentation using
a) Basic Global thresholding
b) Optimal global thresholding or Otsu’s thresholding
