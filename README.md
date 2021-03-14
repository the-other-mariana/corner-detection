# Corner Detection

This is a small notebook code that detects the corners of an image. <br />

## 1. Canny Edges

First, an image is filtered to black and white in order to find its contours. <br />

![image](https://github.com/the-other-mariana/corner-detection/blob/master/output/canny.png?raw=true) <br />

## 2. Harris Corner Detection

Then, using Harris Corner Detection, the image now has the corners detected. <br />

![image](https://github.com/the-other-mariana/corner-detection/blob/master/output/harris.png?raw=true) <br />

## 3. Filter Corners

The Harris corner output generates an array of points in each corner, so we filter it in order to have each corner containing one pixel. <br />

![image](https://github.com/the-other-mariana/corner-detection/blob/master/output/detected.png?raw=true) <br />

## 4. Figure Detection

After some geometry manipulation, we determine the figures present by drawing each type of figure with a different color. <br />

![image](https://github.com/the-other-mariana/corner-detection/blob/master/output/output.png?raw=true) <br />