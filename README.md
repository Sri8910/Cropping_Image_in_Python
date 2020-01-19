# Cropping_Image_in_Python
To crop an Image using "Pillow" libray in python 3.8.1


To Install the pillow library in command prompt for windows 

CODE:

pip3 install Pillow

CODE:

from PIL import Image        #importing image module from pillow library

im=Image.open(r'Image path') # the 'r' attribute is used to avoid unicodeerror

area=(100,200,300,375)       # The four entries represent left,up/top,right,bottom/down pixel coordinates 

im1=im.crop((area))          #To crop the image with respective to pixel value mentioned

im1.show()                   # To show the cropped image

OUTPUT:

ORIGINAL IMAGE:

![plitvice lake](https://user-images.githubusercontent.com/48615002/72682927-a1dae880-3af8-11ea-8f6e-197058468647.jpg)

CROPPED IMAGE:

![Capture](https://user-images.githubusercontent.com/48615002/72683009-93d99780-3af9-11ea-8863-5e8d6685668f.PNG)



