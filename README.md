Training the YOLOv8 Model for Object Detection

This notebook contains the complete process of training and evaluating the YOLOv8 model for the detection of four specific types of objects.  The objective is to train an efficient detector that can correctly identify and classify these objects in different scenarios.
Notebook Flow

1. Environment Configuration
2. Importing the necessary libraries, including Ultralytics YOLOv8.
3. Definition of essential parameters for training.
4. Data Loading and Preparation
5. Structuring the training, validation, and test dataset.
6.Application of image transformations and augmentations.
7. Organization of classes and mapping of annotations for the four types of objects.
8. Training the YOLOv8 Model
9. Hyperparameter configuration: learning rate, number of epochs, batch size, and image size.
9. Use of transfer learning to accelerate training.
10. Monitoring the training with logs of metrics such as loss, accuracy, and IoU (Intersection over Union).
11.Model Evaluation
12. Tests with validation images and inference on unseen images.
13. Generation of performance metrics: mAP (Mean Average Precision) and class confusion.
14. Comparison of the results with other approaches.
15. Visualization of Results
16. Analysis of predictions made by the model on different images.
17.Plotting of bounding boxes and labels for model accuracy validation.
Objective

The trained model was used to automatically identify the four types of objects in the images, enabling applications in surveillance, industrial automation, medical diagnosis, and much more.
