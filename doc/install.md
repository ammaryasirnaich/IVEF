# Installation

### Requirements
All the codes are tested in the following environment:
* Linux (tested on Ubuntu 20.04)
* Python 3.8.10
* PyTorch: 1.9.0a0+c3d40fd
* CUDA 11.3
* Numba v0.56.0
* Cupy v11.3 
* [`spconv v2.0`](https://github.com/traveller59/spconv) 

### Install `mmdetection v1.0.0rc3+0b129d8`

NOTE: Please install `mmdetection3d` framework

a. Clone this repository.
```shell
git clone https://github.com/open-mmlab/mmdetection3d.git
```

b. Install the dependent libraries as follows:

* Install the dependent python libraries:
```
pip install -r requirements.txt
```
Note: Also, the `numba` and `cupy` library packages

