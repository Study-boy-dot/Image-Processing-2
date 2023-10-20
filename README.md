# Image-Processing-2
 Edge Detection & Image Transform

## Execute code
python EdgeDetection_ImageTransfrom.py

## Running Code
![image](https://github.com/Study-boy-dot/Image-Processing-2/assets/80616480/5e804bbc-cd13-41d5-884f-8bf781f1c86b)  

## Edge Detection
Load any image and click the button in GUI
1. **Gaussian Blur** - Doing Gaussian Blur  
2. **Sobel X** - Detect line in image along x-axis  
3. **Sobel Y** - Detect line in image along y-axis  
4. **Magnitude** - Detect line in image along x and y axis  

## Image Transformation
1. **Resize** -
 * From (430,430) to (215,215) and cv2.imshow with (430, 430)
 * window (image center: (108, 108) top left of window)  
2. **Traslation** -
 * Xnew = Xold + 215 pixels = 108 + 215 = 323
 * Ynew = Yold + 215 pixels = 108 + 215 = 323
 * Point C (108, 108) is center of resized image Point C’(323, 323) is new center of image (bottom right of window)(Then overlay with result image of 4.1))  
3. **Rotaion, Scaling** -
 * Center: Center of Image Angle = 45o (counter-clockwise)
 * Scale = 0.5 , window size (430,430)  
4. **Shearing** -
 * Old location: ([[50,50],[200,50],[50,200]])
 * New location: ([[10,100],[100,50],[100,250]])  
