# disparity_map

There are two modes that can be used:
1. Parallel
2. Sequential

The parallel mode is 2.5 times faster than the sequential mode if 7 parallel processes are used.
Paramters can be set at the end of disparity.py

To make the resulting disparity map less heterogenous, we used the median filter
also known as the filter that denoises the salt-and-pepper noise.

Here are a few examples following the execution of our disparity map function of samples from [data]:

![example 1](depth/depth10.png)

![example 2](depth/depth10.png)
