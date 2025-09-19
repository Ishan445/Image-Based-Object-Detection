# Realtime-Object-Recognition
A straightforward Python project for performing real time object detection in images using OpenCV's Deep Neural Network (DNN) module.

It leverages a pre-trained model to identify various objects within an image. The script highlights detections with colored bounding boxes and displays the object's name with its confidence score. Built for flexibility, it is made for processing static images only.

---

# Features

- Pre-trained Model Integration: Loads and utilizes a pre-trained TensorFlow model to perform sophisticated object detection.
- Static Image Analysis: Processes a single image file to accurately identify multiple objects within it.
- Bounding Box Visualization: Draws clean and precise bounding boxes around each object that is successfully detected.
- Confidence Scoring: Labels each detected object not only with its name but also with a confidence score to show the model's certainty.

---

## Project Files

* **Program(OD).ipynb**  
This is the main Jupyter Notebook that contains all the Python code for the project. It loads the model, processes an image, and displays the final output with detections.

* **deploy.prototxt**  
This is a configuration file that outlines the architecture of the neural network. OpenCV uses it to understand the model's structure before loading the pre-trained weights.

* **res10_300x300_ssd_iter_140000_fp16.caffemodel**  
This file stores the pre-trained weights, which are the learned parameters of the network. It essentially contains the "knowledge" the model uses to find objects in an image.

* **coco_class_labels.txt**  
This text file lists all the object names that the model is able to recognize. It's used to map the model's numerical output to a human-readable label like "car".

---

## Output Example

<img width="974" height="472" alt="street" src="https://github.com/user-attachments/assets/8af55536-cec0-4919-acf1-e6faf38410bc" />

---

## Author

**Ishan Zadbuke**   
Developed as part of a computer vision learning project using OpenCV.
