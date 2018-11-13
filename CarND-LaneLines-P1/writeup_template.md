# **Finding Lane Lines on the Road** 

### Reflection

<img src="./test_images_output/00solidWhiteCurve.jpg" width="480px">

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

#### 1st Step. Convert the Image to grayscale 

<img src="./test_images_output/01solidWhiteCurve_Gray.jpg" width="480px">

#### 2nd Step. Apply Gaussian smoothing to the Grayscale Image

kernel size : 5

<img src="./test_images_output/02solidWhiteCurve_Gray_blur.jpg" width="480px">

#### 3rd Step. Apply Gaussian smoothing to the Grayscale Image

---

 My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 




### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
