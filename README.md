# Structure Sensitive and Semantic Alignment Synergistic Enhancement  Network for Remote Sensing Change Detection
This repository contains a simple Python implementation of our paper S2ENet.
![](https://github.com/ahaha-16/S2ENet/blob/main/S2ENet.png)
Prepare the data:

Download datasets SYSU-CD, CLCD, WHU-CD, and LEVIR-CD

Prepare datasets into the following structure and set their path in train.py and test.py
├─Train
    ├─A        ...jpg/png
    ├─B        ...jpg/png
    ├─label    ...jpg/png
    └─list     ...txt
├─Val
    ├─A
    ├─B
    ├─label
    └─list
├─Test
    ├─A
    ├─B
    ├─label
    └─list
