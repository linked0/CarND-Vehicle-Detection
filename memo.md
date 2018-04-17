# Vehicle Detection Project

[//]: # (Image Referenc)
[image-default]: ./memo_images/default.png
[image-luv-ch1]: ./memo_images/LUV_channel-1.png

### 2018.04.17
Default and y_start_stop = [490, None]

![alg text][image-default]
<hr>
LUV channel 1이 HOG에서 가장 성능이 좋음. 96%까지 나온 것으로 보임.
y_start_stop = [490, None]

![alt text][image-luv-ch1]

<hr>
중요 파라미터

* different color feature sets
* different gradient feature sets
* different search window sizes
* different overlap