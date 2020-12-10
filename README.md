# disparity_map

There are two modes that can be used:
1. Parallel
2. Sequential

The parallel mode is 2.5 times faster than the sequential mode if 7 parallel processes are used.
Paramters can be set at the end of disparity.py

To make the resulting disparity map less heterogenous, we used the median filter
also known as the filter that denoises the salt-and-pepper noise.

Here are a few examples following the execution of our disparity map function of samples from [data]:
<img src="https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_map/depth.jpg" alt="drawing" width="100"/>
![example 1](https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_map/depth.jpg =100x)

![example 2](https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_map/depth10.jpg =100x)
