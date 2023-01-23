# Faster-RCNN

In this project, MaskRCNN is implemented which addresses the task of instance seg-
mentation, combining object detection and semantic segmentation into a per-pixel object detection framework. We train the Network on the standard COCO dataset, which has 80 object classes.

### Network Architecture
![image](https://user-images.githubusercontent.com/31537022/214123356-3c1f7736-6f8e-4766-b334-7e5b2e10e380.png)
![image](https://user-images.githubusercontent.com/31537022/214123266-dd7b2860-34c2-4864-98a3-37bc4b93b1f8.png)
![image](https://user-images.githubusercontent.com/31537022/214123152-62cc8d42-6d5e-4ca0-b979-59fab8177afd.png)

### Loss Objective
![image](https://user-images.githubusercontent.com/31537022/214123608-a9a741fd-c9dd-4244-8a00-66fc935cea69.png)

Loss plots, input and output visualization, and mAP can be seen inside the notebook.
