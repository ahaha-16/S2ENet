# Structure Sensitive and Semantic Alignment Synergistic Enhancement  Network for Remote Sensing Change Detection
This repository contains a simple Python implementation of our paper S2ENet.

## Overview
![](https://github.com/ahaha-16/S2ENet/blob/main/S2ENet.png)

## Dataset Preparation
Download datasets [SYSU-CD](https://github.com/liumency/SYSU-CD), CLCD, [WHU-CD](http://gpcv.whu.edu.cn/data/building_dataset.html), and [LEVIR-CD](https://justchenhao.github.io/LEVIR/)

Prepare datasets into the following structure and set their path in train.py and test.py

    
    ├── Train
        ├── A        ...jpg/png
        ├── B        ...jpg/png
        ├── label    ...jpg/png
        └── list     ...txt
     
    ├── Val
        ├── A
        ├── B
        ├── label
        └── list
     
    ├── Test
        ├── A
        ├── B
        ├── label
        └── list
        
## Requirement


    -Pytorch 2.0.1  
    -torchvision 0.15.2  
    -python 3.10.9  
    -Cuda 11.7    

## Test our trained model result
You can directly test our model by our provided S2ENet weights. Download in [Baidu Disk](https://pan.baidu.com/s/1X6a2HmSAQhDV9A_JhtxKpg),pwd:vnm3

## Change Detection Results
![](https://github.com/ahaha-16/S2ENet/blob/main/change%20detection%20results/comparison.png)

## Visualization
![](https://github.com/ahaha-16/S2ENet/blob/main/change%20detection%20results/sysu.png)
![](https://github.com/ahaha-16/S2ENet/blob/main/change%20detection%20results/clcd.png)
![](https://github.com/ahaha-16/S2ENet/blob/main/change%20detection%20results/whu.png)
![](https://github.com/ahaha-16/S2ENet/blob/main/change%20detection%20results/levir.png)
