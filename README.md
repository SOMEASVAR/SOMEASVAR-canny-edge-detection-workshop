# Canny-edge-detection


# NAME: R.SOMEASVAR
# REGISTER NUMBER: 212221230103
# Question:
```
To perform canny edge detection for a image.
```
# PROGRAM:
```
import cv2
import matplotlib.pyplot as plt
a=cv2.imread('1.jpeg',1)
gray=cv2.cvtColor(a,cv2.COLOR_BGR2GRAY)
gaus=cv2.GaussianBlur(gray,(3,3),0)
plt.imshow(gaus,cmap='gray')
plt.title('Original image')
plt.axis('off')
```
```
canny=cv2.Canny(gaus,120,150)
plt.imshow(canny,cmap='gray')
plt.title('Edge detected image using Canny operator')
plt.axis('off')
```
# OUTPUT:
# ORIGINAL IMAGE:
![1](https://user-images.githubusercontent.com/93434149/176170051-99a96f82-1c6a-477c-a698-793346248f23.jpeg)

# GRAY IMAGE:
![Screenshot 2022-06-28 171154](https://user-images.githubusercontent.com/93434149/176170151-d62ff014-205b-4042-97b9-c05bf4ff9b75.jpg)


# CANNY EDGE DETECTION:

![2](https://user-images.githubusercontent.com/93434149/176170171-93f07925-504b-4976-a4a9-e2f23be6ed83.jpg)
# RESULT:
To perform canny edge detection for a image is done successfully.
