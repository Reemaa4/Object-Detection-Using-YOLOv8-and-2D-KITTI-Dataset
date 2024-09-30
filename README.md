# Object-Detection-Using-YOLOv8-and-2D-KITTI-Dataset
comprehensive implementation of object detection using the YOLOv8 model, applied to the 2D KITTI dataset.


# Dataset Description:
"2D Object Detection Evaluation 2012" consists of 7481 training images with their labels and 7518 test images.

# Preprocessing Steps:
1.	Train-Validation Split: 
Split the training images and labels into separate training and validation sets.

2.	Label Conversion: 
Converted the labels from KITTI format to YOLO format (the conversion code is inside ipynb file)

3.	YAML File Creation: 
Created a YAML file (test_dataset.yaml)
specifying the paths for training and validation images, the number of classes (9), and
the class names:['Car', 'Van', 'Truck', 'Pedestrian', 'Person_sitting', 'Cyclist', 'Tram', 'Misc', 'DontCare'].

4.	Image Resizing: 
Resized all images to 640x640 pixels for uniformity during training.

