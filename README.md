# MonaLisa
This was an assignment for Applied Machine Learning class at Cornell Tech. 

Title: Random forests for image approximation

Description:
In this problem, we used random forest regression to approximate an image by learning a function that takes image (x, y) coordinates as input and outputs pixel brightness. This way, the function learns to approximate areas of the image that it has not seen before.

Tasks:
1) To build your “training set” uniformly sample 5,000 random (x, y) coordinate locations.

2) To build the final image, for each pixel of the output, feed the pixel coordinate through the random forest and color the resulting pixel with the output prediction.

3) Repeat the experiment for a random forest containing a single decision tree, but with
depths 1, 2, 3, 5, 10, and 15.

4) Repeat the experiment for a random forest of depth 7, but with number of trees equal to
1, 3, 5, 10, and 100.

5) Experiment with different pruning strategies of your choice.
