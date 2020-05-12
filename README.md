# Histogram-Equalisation-without-using-equalizeHist

This is to understand how histogram equalization works. There is a equalizeHist inbuilt function in cv2 . 

1.Find frequency of each pixel.</br>
2.Find the probability mass fucntion of each frequency.</br> 
3.Find the cumulative histogram of each pixel.</br>
4.Find the cumulative distributive function of each graylevel.</br>
5.Calculating final new pixel value by cdf * (Levels-1).</br>
