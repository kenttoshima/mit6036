# Lab 8
## Section 1
- a. None, since we cannot distinguish whether $x_1$ is bigger or $x_3$ is bigger with only one unit
- b. [[1,0,-1,-1],[-1,0,1,-1],[1,1,0]]; this is possible because with two units we can detect both cases in (a)
- c. [1,1,0,1,0,-1,0,-1,-1,-1]; we need for cases for detecting two sets of diagonal corner difference

## Section 2
- a. draw
- b. [3,4,6,7] --> need to look at two pixels to detect one edge
- c. [9,10,12,13]

## Section 3
- a. f1: detects vertical color change; f2: detects horizontal color change; f3: detects vertical and horizontal color change --> square shapes are seen
- b. f1: right brighter; f2: left brighter; f3: points brighter
- c. if bias is increased, threshold is leaning towards white and vice versa.
- d. When bias is zero it does not change the image. When bias is non-zero, contrast gets clearer
- e. Padding with the same pixel as the edge pixel, two convolution units to detect right edge and left edge, and fully connected layer with weights 0.5 to correct double count of the obejct

## Section 4
- a. np.array([[6,7,0,0],[5,6,7,0],[0,5,6,7],[0,0,5,6]]).T --> since the same weights occurs repeatedly in the matrix, it would be more efficient to use filter
- b. draw diagram!
