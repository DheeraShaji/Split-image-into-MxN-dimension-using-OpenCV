
# Split image into MxN dimension

Spliting an image into smaller patches is useful when the size of the image is too large. Large images can affect the processing and may take longer time to process as well. In such cases, it is better to break down large images into smaller patches for batch processing. There are some in-built functions like image_slicer to crop the image into smaller patches, but with images of JPG extension, it does not support transparency - RGBA (Red, Green, Blue, Alpha - Alpha is transparency). So, there comes a need to either discard the Alpha Channel or to save with some other extension that supports transparency (like PNG). It's not handy when there are thousands of images to work with.


So, here is a simple and effective way to crop the images into patches of m x n dimension.
Given the image path, m, and n values, the cropeed images will get stored to the desired location.

Input: 


![in_img](https://user-images.githubusercontent.com/78141360/190328547-593096d5-329d-413f-aa40-2dd020f7d1d0.png)


Output: Get 9 splitted images


![im-out](https://user-images.githubusercontent.com/78141360/190328557-8a28f509-3daa-43d4-a1c2-b47f193838ba.png)


