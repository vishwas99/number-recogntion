# number-recogntion
OCR on hand written numbers from images, video and a canvas to draw with cursor
1.run main.py and choose the options

2.the model can only detect the images with white color on black background so we convert them into grayscale and invert them with a small code snippet
  %%
    IMAGE = CV2.IMREAD('IMAGE.PNG')
    IMAGE = INT(IMAGE) - 255
   %%
 
3.to use the live video 
   -> give 0 as parameter inside CV2.CAPTURE()
   -> or else you can use ip cam and give the ip address of the cam instead of 0

4.Model is saved as model (accuracy achived is 96 percent) it has only 1 hidden layer you can improve it by adding more layers and using your own model
