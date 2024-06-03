# Fog-Image-Creation
This project is about adding fog/Haze effects in the image. 
Keywords:
1. Adding fog in the images
2. Adding Haze in the images
3. Convert original images to Fog/Hazzy images.
4. Adding perlin noise in the image for Fog creation.

Literature survey on "Towards simulating fog and Hazzy images and Evaluating their authenticity"  - which produces based on the elevation of the image pixel in the input image.

So, basically the framework based on "Atmospheric scattering model" which can simulate fog images at any elevations in the image. Instead of using depth map of the images, using the depth information of images, this calculates the elevation of each pixel in the images using perspective projection transformation and then compute the thickness Ht and the elevation of the camera Hc.

The estimation of elevation of the pixels in the image gives accurate distance of objects from the camera. 

 ![image](https://github.com/prabhuiitdhn/Fog-Image-Creation/assets/19517005/75a074c8-bf4e-4915-a5c3-8521fd6fbb2b)




