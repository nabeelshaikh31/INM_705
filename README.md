# INM_705 - Deep Learning for Image Analysis 
## "Hand Gesture Recognition using YoloV5 (Object Detection)"

A computer vision technique known as object detection is used to find occurrences of objects in pictures or videos. Due to its adaptability, object detection is one of the most often used computer vision models. While image classification allows us to categorise (classify) whether an object is there in the image or not based on the likelihood, object detection basically identifies the object with a bounding box in the image.

To generate useful results, object detection algorithms frequently use machine learning or deep learning. Humans can quickly identify and pinpoint objects of interest when viewing photos or videos. Using a computer, object detection aims to simulate this intelligence of humans. This field has advanced significantly recently and can now detect and categorise items more accurately than humans in some situations using deep learning and neural networks.

For my coursework, I will be working on detecting specific objects from an image or a video. Object detection includes detecting the location of the object in the image by drawing a bounding box and also classifying the detected object to a particular class or label. The dataset that I will be working on is a custom built dataset where the images are downloaded from the source: “here”, for the training I have used 272 images, for validation I have used 92 images and for testing I have used 26 images. The dataset consists of 3 classes in total, i.e. “ok” gesture, “peace” gesture, and “dislike” gesture. We need to use bounding box annotations to guide the learning of our object detector. Each object that we want the detector to view is enclosed in a box, and we label each box with the object class we want it to infer. To do so, I made use of a free-to-use online tool called “makesense.ai” for manually and accurately creating the bounding box and labelling the train and validation images from my custom dataset in a yolo format i.e. “<object_class> <x> <y> <width> <height>”.

I will be implementing a You Only Look Once (YOLOv5) model. A family of compound-scaled object detection models called YOLOv5 was developed by Ultralytics by using the COCO dataset and includes basic features for Test Time Augmentation (TTA), model ensembling, and hyperparameter evolution. It was found that YOLOv5 outperforms YOLOv4 and YOLOv3 in terms of accuracy. The detection speed of YOLOv3 was faster compared to YOLOv4 and YOLOv5 and the detection speed of YOLOv4 and YOLOv5 were identical.

I will be referring to the PyTorch Tutorial for object detection by Ultralytics. The link to the tutorial can be found “here”.


