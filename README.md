## :computer: Image Processing Tasks 

These tasks are performed without using inbuilt Python libraries. The only libraries used are Numpy & PIL

---
### :city_sunset: Image Rotation

The image is rotated by angles which are multiples of 90 degrees
  
![Original Image](https://user-images.githubusercontent.com/64036185/92142268-32203080-ee31-11ea-9c30-9fa8f51d3b74.png) 

|<img width="350" height="300" src="https://user-images.githubusercontent.com/64036185/92142385-5d0a8480-ee31-11ea-84e4-23cd69a9b345.png">|
|:---:|
|270 Degrees Clockwise|

### :sunrise: Applying Kernels

The Kernel filters are doing the following tasks:
1. Blurring (Normal Blur, Box Blur & Gaussian Blur)
2. Sharpening the Image

![Original Image](https://user-images.githubusercontent.com/64036185/92143212-8ed01b00-ee32-11ea-8315-c57b111ce552.png)

**Output**
|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92144804-deafe180-ee34-11ea-9ee6-259f5dbe4326.png">|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92144938-14ed6100-ee35-11ea-888f-bb64c2f35fe3.png">|<img width="300" height="300" src="https://user-images.githubusercontent.com/64036185/92143827-6f85bd80-ee33-11ea-831d-e9a08b36d204.png">
|:---:|:---:|:---:|
|Box Filter|Gaussian Filter|Sharpen|

### :city_sunset: Edge Detection

**Original Images**

![Cube](https://user-images.githubusercontent.com/64036185/92311996-1c9a3a80-efda-11ea-933c-aa736515b5af.jpg)

![Dog](https://user-images.githubusercontent.com/64036185/92312000-3045a100-efda-11ea-94e9-35a21ea14d18.png)

**Output**

|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312033-a8ac6200-efda-11ea-86b2-1f3db1b96094.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312045-c679c700-efda-11ea-8ac1-ca712ed6ae4a.png">|<img width="208" height="203" src="https://user-images.githubusercontent.com/64036185/92312054-d98c9700-efda-11ea-8af6-5acf3981e815.png">
|:---:|:---:|:---:|
|Vertical Edge|Horizontal Edge|Sobel|



