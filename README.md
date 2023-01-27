# VR-RL
## Introduction

we proposed a method to expand the data and real-time training architecture through VR to improve the accuracy of the model and reduce labor costs and time consumed.

In addition, it can also complete labeling tasks rapidly, and even 3D object detection can be quickly obtained.


## Installation
### Docker image
If you would rather not have to install anything, you can pull the docker image.
```
docker pull ...
docker run ...
```
### Install from source
1. computer request first: [Unreal](https://www.unrealengine.com/en-US/download) ```4.27.X```, [Airsim](https://github.com/Microsoft/AirSim) ```1.6```
2. clone and submodule
We use YOLOv7 to train real time , so we include YOLOv7 as a submodule.
```
git clone ...
cd ...
git submodule init
git submodule update
```
3. Download a pretrained model from YOLOv7
```
wget https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt
```

## Traing
```
python train.py
```

## Demo
Demo for image:
```

```
Demo for video:
```

```
## Result Video
{%youtube E8Nj7RwXf0s %}

## Citation
## License
## Reference