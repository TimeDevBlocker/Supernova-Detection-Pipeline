# Supernova-Detection-Pipeline

## Introduction
This is a work-in-progress supernova detection pipeline. Currently I'm stil working on training the detection model, and everything will be uploaded after I finish all the work left.

## Functions
1. Image Subtraction (Newly-acquired Image - Reference Image) **Status: Finished**
2. Object(Transient) Detection (Based on YOLOX)   **Status: In-progress**
3. Eliminating False Positives (Flares, satellites, etc.) **Status: Incomplete**
4. Performing Precise Photometry **Status: Incomplete**
5. Reporting to User for Futher Actions **Status: Incomplete**

## References and Credits
[Yin K, Jia J, Gao X, Sun T, Zhou Z. Supernovae Detection with Fully Convolutional One-Stage Framework. Sensors. 2021; 21(5):1926](https://www.mdpi.com/1424-8220/21/5/1926)   

[李卫东, 赵昭旺. 北京天文台超新星巡天系统:Ⅰ.巡天设备及软件[J]. 中国科学, 1998, 41(3):283-288.](http://qikan.cqvip.com/Qikan/Article/Detail?id=2931272)  
  
[YOLOX](https://github.com/Megvii-BaseDetection/YOLOX)

The targets of the dataset were provided from the Pan-STARRS NEO survey and made public via via http://star.pst.qub.ac.uk/ps1threepi/.  
Operation of the Pan-STARRS1 telescope is supported by the National Aeronautics and Space Administration under Grant No. NNX12AR65G and Grant No. NNX14AM74G issued through the NEO Observation Program.

