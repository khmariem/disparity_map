# disparity_map

There are two modes that can be used:
1. Parallel
2. Sequential

The parallel mode is 2.5 times faster than the sequential mode when 7 parallel processes are used. The speed itself also depends on the parameters, but in the table below, we fix the parameters in order to compare the sequential and parallel modes.
|Example|Sequential|Parallel|
|-------|:--------:|-------:|
|[example1](./data/im0.png)|134 s|55 s|
|[example2](./data/imL.png)|31 s|12 s|

Parameters can be set at the end of [disparity.py](disparity.py)

To make the resulting disparity map less heterogenous, we used the median filter
also known as the filter that denoises the salt-and-pepper noise.

Here are a few examples following the execution of our disparity map function on sample images from [data](./data):
<img src="https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_map/depth.jpg" alt="drawing" width="400"/>
<img src="https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_color_map/depth.jpg" alt="drawing" width="400"/>
<img src="https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_map/depth10.jpg" alt="drawing" width="400"/>
<img src="https://raw.githubusercontent.com/khmariem/disparity_map/main/depth_color_map/depth11.jpg" alt="drawing" width="400"/>
