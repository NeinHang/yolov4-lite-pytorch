# yolov4-lite-pytorch

## 介绍
yolov4-lite-pytorch

## 软件架构
软件架构说明
该工程主干是来自csdn的Bubbliiiing大佬[https://blog.csdn.net/weixin_44791964?spm=1001.2014.3001.5509]的github工程
[https://github.com/bubbliiiing/mobilenet-yolov4-pytorch]

具体操作步骤请转移到该工程哈（这里工程仅仅加入了shufflenetv2的骨干）

## 性能情况
| 训练数据集 | 权值文件名称 | 测试数据集 | 输入图片大小 | mAP 0.5:0.95 | mAP 0.5 |
| :-----: | :-----: | :------: | :------: | :------: | :-----: |
| VOC07+12 | [yolov4_mobilenet_v1_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v1_voc.pth) | VOC-Test07 | 416x416 | - | 79.72
| VOC07+12 | [yolov4_mobilenet_v2_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v2_voc.pth) | VOC-Test07 | 416x416 | - | 80.12
| VOC07+12 | [yolov4_mobilenet_v3_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v3_voc.pth) | VOC-Test07 | 416x416 | - | 79.01
| VOC07+12 | [yolov4_ghostnet_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_ghostnet_voc.pth) | VOC-Test07 | 416x416 | - | 78.69
| VOC07+12 | [yolov4_densenet121_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_densenet121_voc.pth) | VOC-Test07 | 416x416 | - | 83.99

| VOC07+12 | [yolov4_mobilenet_v1_voc.pth](https://github.com/bubbliiiing/mobilenet-yolov4-lite-pytorch/releases/download/v1.0/yolov4_mobilenet_v1_voc.pth) | VOC-Test07 | 416x416 | - | 79.72

## Reference

https://github.com/bubbliiiing/mobilenet-yolov4-pytorch