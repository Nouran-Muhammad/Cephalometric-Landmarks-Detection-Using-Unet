# Cephalometric-Landmarks-Detection-Using-Unet

This is a project for detection of the 19 cephalometric landmarks on X-ray images using semantic segmentation using Unet
![cepha landmarks](https://user-images.githubusercontent.com/61350907/208296118-4539af0d-f553-407e-998b-d8ded05b73c0.jpg)

First Trial 
the use of 1 channel binary mask where 1's represent a white square with the landmark position as the centre, and 0's represent the background
Dice loss function was used

Second Trial (ongoing)
The mask consists of 20 channels representing the 19 landmarks and the background and was filled with the below function
![Screenshot 2022-12-16 202339](https://user-images.githubusercontent.com/61350907/208296222-cf7afa5d-88dc-4845-be87-aa2a403d1c39.png)
