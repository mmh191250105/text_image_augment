##工具复现，文本图像扩增

## 安装依赖

- [Python](https://www.python.org/) 3.6.4
- [Numpy](https://numpy.org/) 1.14.0

## 运行过程
- demo.py为程序入口
-demo.png为程序输入，程序将对其进行图像扩增操作

## 功能模块
- demo.py运行程序

- augment.py对图像进行三种操作

- warp_mls.py根据augment中的操作进行计算，生成新的图片


## 运行效果

- 原图

![](imgs/demo.png) 

- Distortion

![](imgs/distort.gif) 

- Stretch

![](imgs/stretch.gif)

- Perspective

![](imgs/perspective.gif)


## 原论文公布的代码
原文源码： https://github.com/Canjie-Luo/Text-Image-Augmentation.git.
