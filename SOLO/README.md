## Intro
Instance segmentation can be thought of as a combination of object detection and semantic segmentation. 
In this project, an instance segmentation framework know as SOLO (Segmenting Object by LOcations) is implemented. In a similar manner to YOLO, SOLO produces mask predictions on a dense grid. This means that, unlike many other segmenation frameworks (e.g. Mask-RCNN), SOLO directly predicts the segmentation mask without proposing bounding box locations. 

SOLO has 2 branches - the category branch and the mask branch
![image](https://user-images.githubusercontent.com/31537022/200158789-51d5eae6-ff25-4c5b-84f5-90dbe8f43c01.png)


## Model Architecture
* Category Branch:

![image](https://user-images.githubusercontent.com/31537022/200158800-122d4c2b-c514-4d55-a97e-57ccc1947c5a.png)

* Mask Branch:

![image](https://user-images.githubusercontent.com/31537022/200158816-40cf7553-d27d-41b8-9edc-293c403ed62a.png)


## Training Objective
![image](https://user-images.githubusercontent.com/31537022/200158844-43fa621d-69b7-44bc-b633-8a0d22d9b42d.png)


## Results
![image](https://user-images.githubusercontent.com/31537022/200158876-54480b75-e645-4d06-8278-5058eb0d6aab.png)


## Loss Curves
![image](https://user-images.githubusercontent.com/31537022/200158865-21e725f7-ab68-4dcc-9dd9-e6e8503f0d79.png)
