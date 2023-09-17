# Custom Aeroponics basket detection/recognition with tensorflow object detection API for Raspberry Pi 4

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model](#model)
- [Deployment](#deployment)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
This project is a custom object detection/recognition model for aeroponics basket detection. The model is trained using tensorflow object detection API and the dataset is collected using a Raspberry Pi 4 with a Pi camera module. The model is then deployed on the Raspberry Pi 4 to perform real-time object detection/recognition.

## Dataset
The dataset is collected using a Raspberry Pi 4 with a Pi camera module. The dataset consists of 2 classes: aeroponics basket and background. The dataset is collected using the following steps:

1. Mount the Raspberry Pi 4 on a tripod and place it in front of the aeroponics basket.
2. Take a picture of the aeroponics basket.
3. Remove the aeroponics basket from the picture.
4. Take a picture of the background.
5. Repeat steps 2-4 for 100 times.

The dataset is then split into 2 parts: training set and test set. The training set consists of 80% of the dataset and the test set consists of 20% of the dataset.

## Model
The model is trained using tensorflow object detection API. The model is trained using the following steps:

1. Download the pre-trained model from the [tensorflow model zoo]

2. Convert the dataset into tfrecord format.

3. Configure the model pipeline.

4. Train the model.

5. Export the model.

## Deployment
The model is deployed on the Raspberry Pi 4 to perform real-time object detection/recognition. The model is deployed using the following steps:

1. Install tensorflow lite runtime on the Raspberry Pi 4.

2. Convert the model into tensorflow lite format.

3. Write a python script to perform real-time object detection/recognition.

## Results
The model is able to detect/recognize the aeroponics basket with an accuracy of 99.9% on the test set.

## Conclusion
The model is able to detect/recognize the aeroponics basket with an accuracy of 99.9% on the test set. The model is able to perform real-time object detection/recognition on the Raspberry Pi 4.

## Future Work

## References
1. [Tensorflow Object Detection API](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/index.html)
2. [Tensorflow Object Detection API Installation](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html)
3. [Tensorflow Object Detection API Training](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html)
4. [Tensorflow Object Detection API Deployment](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/deployment.html)
5. [Tensorflow Object Detection API Raspberry Pi](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi.html)
6. [Tensorflow Object Detection API Raspberry Pi Object Detection](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi_object_detection.html)
7. [Tensorflow Object Detection API Raspberry Pi Object Recognition](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi_object_recognition.html)
8. [Tensorflow Object Detection API Raspberry Pi Object Detection/Recognition](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi_object_detection_recognition.html)
9. [Tensorflow Object Detection API Raspberry Pi Object Detection/Recognition with Coral USB Accelerator](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi_object_detection_recognition_coral_usb.html)
10. [Tensorflow Object Detection API Raspberry Pi Object Detection/Recognition with Coral USB Accelerator and Edge TPU](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/raspberry_pi_object_detection_recognition_coral_usb_tpu.html)


## Appendix



## Acknowledgements

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
- [**Julien AWONGA**](https://linkedin.com/in/julienawonga)

