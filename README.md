# YOLOv5 with Pascal VOC Dataset

This repository demonstrates how to train and evaluate YOLOv5 on the Pascal VOC dataset for object detection. The tutorial includes dataset preparation, model training, validation, and inference, enabling users to replicate the results and adapt them for custom object detection tasks.

Note: This tutorial uses 20% of the Pascal VOC dataset for demonstration purposes to reduce training time. For full training, update the data/voc.yaml file to use the original train.txt and val.txt files.

## **Features**

- Prepares the Pascal VOC dataset for YOLOv5 using XML to YOLO annotation conversion.
- Trains YOLOv5 on the Pascal VOC 2012 dataset.
- Evaluates the model using precision, recall, mAP, and confusion matrix.
- Runs inference to detect objects in test images.

---

## **Installation**

1. Clone this repository and navigate to the YOLOv5 directory:
   ```bash
   git clone https://github.com/joshmoy/object-detection.git
   cd object-detection
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have Python 3+ and CUDA (if using a GPU).


## **Acknowledgments**

- YOLOv5 by [Ultralytics](https://github.com/ultralytics/yolov5).
- Updated YOLOv5 for VOC dataset [here](https://github.com/joshmoy/yolov5.git)
- Pascal VOC dataset: [http://host.robots.ox.ac.uk/pascal/VOC/](http://host.robots.ox.ac.uk/pascal/VOC/).

---

## **License**

This repository is licensed under the MIT License. See the LICENSE file for details.

