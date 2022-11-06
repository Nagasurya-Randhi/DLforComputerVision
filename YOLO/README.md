## Intro
Object detection is a fundamental task in computer vision. The problem of object recognition essentially consists of first localizing the object and then classifying it with a semantic label. In recent deep learning based methods, YOLO is an extremely fast real time multi object detection algorithm.

In this project, we provide 10K street scene images with correponding labels as training data. The image dimension is $128 \times 128 \times 3$, and the labels include the semantic class and the bounding box corresponding to each object in the image.

## Model Architecture
![image](https://user-images.githubusercontent.com/31537022/200158311-78b482aa-1a2a-40f0-9d53-d7eeecf54964.png)


## Training
![image](https://user-images.githubusercontent.com/31537022/200158334-0d8dd41e-65c8-4850-bd29-6fddeb6df27c.png)


I could only train for 20 epochs so the model's performance isn't very robust. An example from inference visualized is shown below:
![image](https://user-images.githubusercontent.com/31537022/200158422-1c36009d-8e2f-40ee-9c4c-a30316959340.png)
