# processingSobelFilter
Sobel Filter demonstrated in Processing

https://en.wikipedia.org/wiki/Sobel_operator

Load an image when prompted, then move mouse over left hand side.  

The calculated gradient of the image is stored as two sobel tests -the X axis test in the red channel and the Y axis test in the blue channel.

Given a point on the image and a direction, I can quickly calculate the slope of the gradient.  That gradient is displayed to the user as dark (decreasing), grey (no slope), and light (increasing).

In real time I can easily display the gradient at every point on the image, using the direction from the center of the image to the user's cursor.

I wrote this for the weaving algorithm @ https://github.com/i-make-robots/weaving_algorithm
