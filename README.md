# Histogram-Equalisation-without-using-equalizeHist

There is a equalizeHist inbuilt function in cv2 but this is to understand how histogram equalization works.

1.Find frequency of each pixel.</br>
2.Find the probability density fucntion of each frequency.</br>
3.Find the cumulative histogram of each pixel.</br>
4.Find the cumulative distribution probability of each pixel.</br>
5.Calculating final new pixel value by cdf * (no of bits).</br>
6.Replace it with oroginal values.</br>
