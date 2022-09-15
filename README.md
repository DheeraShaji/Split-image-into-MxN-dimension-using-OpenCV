
# Split image into MxN dimension

Spliting an image into smaller patches is useful when the size of the image is too large. Large images can affect the processing and may take longer time to process as well. In such cases, it is better to break down large images into smaller patches for batch processing. There are some in-built functions like image_slicer to crop the image into smaller patches, but with images of JPG extension, it does not support transparency - RGBA (Red, Green, Blue, Alpha - Alpha is transparency). So, there comes a need to either discard the Alpha Channel or to save with some other extension that supports transparency (like PNG). It's not handy when there are thousands of images to work with.


So, here is a simple and effective way to crop the images into patches of m x n dimension.
Given the image path, m, and n values, the cropeed images will get stored to the desired location.

Input: 
![image](https://user-images.githubusercontent.com/78141360/190328240-4d3538ad-712c-4f29-963b-cb8921eb5491.jpeg)

