# IVEF
Lidar-Based Intensity-Aware Outdoor 3D Object Detection is centered on voxel-wise lidar Intensity historgram features. This intensity feature is contactinated with the geometric feature for robust feature map for the detection pipleline. 
The code is based on the [`[mmdetection3d]`](https:https://github.com/open-mmlab/mmdetection3d) framework. 
 


**LiDAR-Based Intensity-Aware Outdoor 3D Object Detection**


|![3D Detection pipeline diagram](doc/3ddetectpipline.png) |
|:--:|
| * 3D Detection Pipeline* |



|![Intensity-Based Voxel Feature Extractor](doc/intensity_vfe_encoder.jpeg) |
|:--:|
| * The Intensity-Based Voxel Feature Extractor* |




## Overview
- [Model Zoo](#model-zoo)
- [Installation](#Installation)
- [Acknowledgement](#acknowledgement)
- [Citation](#citation)



## Model Zoo

### KITTI 3D Object Detection Baselines
Selected supported methods are shown in the below table. The results are the 3D detection performance of Hard difficulty on the *val* set of KITTI dataset.
* The model is trained on 1 NVIDIA RTX 3080 GPU and PyTorch 1.9.0a0+c3d40fd.

|                                        Config | training time | Car@R40 | Pedestrian@R40 | Cyclist@R40  | log | download |
|---------------------------------------------|----------:|:-------:|:-------:|:-------:|:----:|:---------:|
| [Config]([https://drive.google.com/file/d/1iV94qwyPfMCrk_q18xwpQHEHnD00LHg8/view?usp=sharing](https://drive.google.com/file/d/1-07QAJD6pbLEoamdJpAywHnq2GlHcaYb/view?usp=drive_link)) |~16 hours| 74.26 | 47.90 | 61.94 | [log]([https://drive.google.com/file/d/1pOjS4S6YHOUdk93XdFVlm9fmF15qZp5q/view?usp=share_link](https://drive.google.com/file/d/1-07QAJD6pbLEoamdJpAywHnq2GlHcaYb/view?usp=drive_link)) | [model]([https://drive.google.com/file/d/1wP5hyyhzw9g0-1EmEBJB7PSOlo5OoRl8/view?usp=share_link](https://drive.google.com/file/d/1fVKxGmT0unPrqBrOEXvmj39TRhLX6oud/view?usp=drive_link)) |


## Installation
Please refer to [install.md](doc/install.md) for the installation of `Intensity-Based feature encoder`.

## Acknowledgement
We would like to thank the authors of[`[mmdetection3d]`](https:https://github.com/open-mmlab/mmdetection3d) for their open source release of their codebase.

## Citation
If you find this project useful in your research, please consider citing:
```
@article{PDV,
    title={Lidar-Based Intensity-Aware Outdoor 3D Object Detection },
    author={Ammar Yasir Naich and
            Jesus Requena Carrion},
    journal={-},
    year={2022}
}
```
