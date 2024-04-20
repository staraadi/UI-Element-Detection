# UI Element Detection using YOLOv7

This repository contains everything required for UI element detection using YOLOv7.

## Dataset
The dataset, **UI-element-Detect-6**, is already included in this repository. You can also download it [here](https://universe.roboflow.com/uied/ui-element-detect/dataset/6#).

## Trained Model Weights
The weights of the trained model after 2 epochs with a batch size of 16 are available at `runs/train/exp/weights/best.pt`. It's recommended to train the model for at least 20 epochs for better performance, but it wasn't trained beyond 2 epochs due to limited resources.

## Test Set Results
The results on the test set of the dataset can be found at `runs/detect/exp2`.

## Evaluation Images Results
The results on evaluation images of the dataset are available at `runs/detect/exp`.

## Colab Notebook
To execute the repository, refer to the Colab notebook file, `Training_YOLOv7_on_UI_Element_detection_Dataset.ipynb`, which contains all the necessary actions.

## Video Walkthrough
For an overview and walkthrough, watch the video [here](https://drive.google.com/file/d/1KVXE3TM1fPOUze0YBhTB7XIHOSySholn/view?usp=sharing).
