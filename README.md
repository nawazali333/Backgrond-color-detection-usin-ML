# Backgrond-color-detection-usin-ML

In this project our aim is to detect the background color of the noisy image ,which it may contain the multiple colors in the the given image

Ever wondered how the Instagram stories pick a background automatically when you add an image?! Well, they analyze your picture through 
different algorithms and produce a background matching with the image. They primarily use the “colours” present in the image to process 
the output.

In this, we simply separate the RGB matrices into separate colour channels and then do a frequency count for each pixel value in the 
3 RGB matrices individually using the Counter() function. After that, you select the 10 most frequent values present and take their average
to get the resultant pixel value. Finally, just produce a blank image using np.zeros() and fill it with the background colour obtained 
to show the final result.
