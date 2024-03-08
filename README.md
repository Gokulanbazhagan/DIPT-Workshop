# DIPT-Workshop1
#Original image:
```
#Nmae:Gokularamanan k
#Reg no:212222230040
import cv2
import numpy as np
img=cv2.imread("down.jpg")
print(img.shape)
```
#orinal to greyscale:
```

img = cv2.imread('gokul.jpg',1)
img = cv2.resize(img,(300,200))
cv2.imshow('Original Image',img)

gray2 = cv2.cvtColor(img,cv2.COLOR_RGB2GRAY)
cv2.imshow('RGB2GRAY',gray2)

cv2.waitKey(0)
cv2.destroyAllWindows()
```
![image](https://github.com/Gokulanbazhagan/DIPT-Workshop/assets/119518996/6f328d7b-47bb-4759-8939-c15f3b6242f2)

#grey scale to hsv:
```

img = cv2.imread('gokul.jpg')
img = cv2.resize(img,(300,200))

img = cv2.cvtColor(img,cv2.COLOR_BGR2HSV)
cv2.imshow('Original HSV Image',img)

RGB = cv2.cvtColor(img,cv2.COLOR_HSV2RGB)
cv2.imshow('2HSV2BGR',RGB)

BGR = cv2.cvtColor(img,cv2.COLOR_HSV2BGR)
cv2.imshow('HSV2RGB',BGR)

cv2.waitKey(0)
cv2.destroyAllWindows()
```
![Screenshot 2024-03-08 093721](https://github.com/Gokulanbazhagan/DIPT-Workshop/assets/119518996/f64f114a-7bb1-418b-b969-40667c3e7269)

![image](https://github.com/Gokulanbazhagan/DIPT-Workshop/assets/119518996/3cac7c1c-9e9d-4b00-9ec5-1b402f4d8917)
