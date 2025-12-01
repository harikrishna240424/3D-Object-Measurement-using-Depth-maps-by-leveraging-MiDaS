  This project aim is to measure multiple objects using a single camera by extracting the depth map.
We use apply DoG filter for histogram analysis to find good binary threshold points to separate objects.
Further, we use Shi Tomasi algorithm for bounding box.
Finally, we perform linear tranformations on the pixel coordinates to real world coordinates, provided we have sensor dimensions.
