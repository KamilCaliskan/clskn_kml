import cv2 as cv
import numpy as np

img1=cv.imread('1245.jpg')
img2=cv.imshow('6789.jpg')
assert img1 is not None
assert img2 is not None

imagebldg= cv.addWeighted(img1,0.4,img2,0.6,0)


cv.imshow('image',imagebldg)
cv.waitKey(0)
cv.destroyAllWindows()
