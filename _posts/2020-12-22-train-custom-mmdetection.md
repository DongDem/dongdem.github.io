---
layout: post
title: How to train mask face detection using mmdetection framework
#subtitle: Excerpt from Soulshaping by Jeff Brown
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [mmdetection, mask-face]
---

Today, I will write the tutorial to develop mask face detection using mmdetection. Firstly, we must collect the mask face data and lable it.  Because the mmdetection use COCO format so after data is labeled, we must convert data to COCO format

## Preapare dataset
- We can download the labeled data (https://github.com/AIZOOTech/FaceMaskDetection)or raw data (WIDER Face or MAFA), then annotate it.
- We use labelImg (https://github.com/tzutalin/labelImg) to annotate.
  - Set `class name` is `mask` and `no mask`
  - We will get the xml file corresponding 
## Install mmdetection
- Firstly, we will install conda to handle environment for project (https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart)
- We can follow this post to install mmdetection (https://github.com/open-mmlab/mmdetection/blob/master/docs/get_started.md)
## Training and visualizing


