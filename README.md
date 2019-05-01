# SDNN

A Darknet implementation of SDNN detection framework . This repository is based on the [darknet](<https://github.com/AlexeyAB/darknet>).

## Introduction

In this repository,  we introduce a new one stage approach, named SDNN, to detect objects with multiple successive frames in video. Additionally, the network fuses the context information of multiple frames, and combines predictions from
multi-scale feature maps at different layers, and trains the whole network in an end-to-end way. Experimental results on a surveillance video dataset demonstrated that the proposed SDNN outperforms state-of-the-art methods, considering the mAP of all category.

More details described in our paper ***Semi-supervised Deep Neural Network for*** ***Object Detection in Video Surveillance Systems***

**Note**: As shown in our GitHub, we released our model first, and the rest source code will follow. The model of which is available on BaiduYun. Link: https://pan.baidu.com/s/1xMHoaSWdWaiZ3-WoVEIQXw Code: ie6x

## Network

![](https://p.qlogo.cn/qqmail_head/Mr4g5VUXVHib5Y2rCUPPwxUziaw14Fs3g74pxqEWNJdI5okEFmpHNdaLnGFqLrwDEtNSD5a8drc8Q/0)

## Experiment

As shown in the figure below, the proposed SDNN achieved the best performance, considering the value mAP.

![](https://p.qlogo.cn/qqmail_head/Mr4g5VUXVHib5Y2rCUPPwxUziaw14Fs3g74pxqEWNJdI5HgNXdQH4ic3EwDnytPX0gxQjOqWYOyK8s/0)

