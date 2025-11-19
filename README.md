# Zombie Detector

This repo contains Zombie Detector trained on custom annotated images based on show Walking Dead and similar CG based images. We used makesense.ai to create bounding boxes and annotations for both RetinaNet and Yolo format.

We used Keras-CV in this project to train our models. We trained both RetinaNet and YoloV8 using multiple backbone models and got best performance with RetinaNet with ResNet-101. We obtained a mAP@0.5 of 0.416 and credible visual bounding boxes and scores for zombies. But we can indeed improve the performance of model by getting more data as 26 images were not enough for training. We could also switch to a ViT based object detection and use LoRA for our task.
