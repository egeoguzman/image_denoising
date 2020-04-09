# image_denoising
Image Denoising by applying averaging method with Python and OpenCV libraries.

**What is Gaussian Noise?**

- Gaussian Noise is a statistical noise having a probability density function equal to normal distribution, also known as Gaussian Distribution. It is also called as electronic noise because it arises in amplifiers or detectors.

- Gaussian noise generally disturbs the gray values in digital images.
- In Gaussian noise, a normally distributed random value is added to each pixel.

Our input is shown as below:

![PIC01](https://user-images.githubusercontent.com/32989239/78870141-588e9b00-7a4e-11ea-8174-d83fab555110.jpg)

**Noise Reduction By Averaging**

We have multiple images with different noise patterns. We are going to apply averaging technique. Taking the average  corresponding pixels will cause the noise to vanish.

Just sum up all images and divide by number of images.

<img width="777" alt="Screen Shot 2020-04-09 at 10 37 10" src="https://user-images.githubusercontent.com/32989239/78870033-27ae6600-7a4e-11ea-8368-6c7eb9f0e691.png">


The more images means the better the noise removal. If you have infinite number of  cases , then you may be able to remove all noises exactly.

**OUTPUT**

![output_80_images](https://user-images.githubusercontent.com/32989239/78870333-9db2cd00-7a4e-11ea-934b-8d2b284efc14.jpg)

**CONCLUSION**

As we can see, most of the noise is vanished by using averaging technique. When our number of images is increase, number of vanished noises is increase too. If we drop more image to the function as an input, we may get smoother images with less noise. You can see the example models of the denoising by averaging technique as a graphics as shown below.


![image_model](https://user-images.githubusercontent.com/32989239/78870238-7a881d80-7a4e-11ea-851d-ae909919867f.png)
