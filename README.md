# UI Element Detection using YOLOv7

This repository contains everything required for UI element detection using YOLOv7.

## Cloning Instructions

After cloning this repository, follow these steps. Google Drive link is mentioned below-:

1. **Move Dataset**: 
   - Download the dataset from the provided link.
   - Move the downloaded dataset into the cloned repository.
   - Ensure that the dataset is placed in the same directory structure as it is in the provided public drive link.

2. **Download and Move Trained Weights**:
   - Download the trained weights from the provided Google Drive link.
   - Move the downloaded weights file to the cloned repository, maintaining the same directory structure as in the public drive link.
   - (Note) The weights of the trained model are after 2 epochs with a batch size of 16 which is available at `runs/train/exp/weights/best.pt` in the drive link. It's recommended to train the model for at least 20 epochs for better performance, but it wasn't trained beyond 2 epochs due to limited resources.

3. **Clone COCO Starting Checkpoint**:
   - Clone the COCO starting checkpoint into the current cloned repository. You can download it [here](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7_training.pt).

4. **Set Up Environment**: Set up the necessary environment and dependencies by installing requirement.txt.

5. **Train Model & Evaluate Model**: To execute the repository, refer to the .ipynb file, `Training_YOLOv7_on_UI_Element_detection_Dataset.ipynb`, which contains all the necessary actions.

## Folder Structure

yolov7/
├── UI-element-Detect-6/
│   ├── ...
│   └── ...
├── runs/
│   ├── detect/
│   │   ├── exp2/
│   │   │   ├── ...
│   │   │   └── ...
│   │   └── exp/
│   │       ├── ...
│   │       └── ...
│   └── train/
│       └── exp/
│           └── weights/
│               └── best.pt
├── yolov7_training.pt
├── Training_YOLOv7_on_UI_Element_detection_Dataset.ipynb
└── README.md


## Google Drive Folder Link

You can access the YOLOv7 folder containing the dataset, evaluation images, results, code, etc., [here](https://drive.google.com/drive/folders/10giALgHW5ut8JMJj2nFHS7x_dyiORZQQ?usp=sharing).
## Dataset

The dataset, **UI-element-Detect-6**, is already downloaded and preprocessed. You can download it [here](https://universe.roboflow.com/uied/ui-element-detect/dataset/6#).

## Test Set Results

The results on the test set of the dataset can be found at **runs/detect/exp2** within the folder.

## Evaluation Images Results

The results on evaluation images are located at **runs/detect/exp** within the folder.

## Trained Model Weights

The trained weights of the model are stored at **runs/train/exp/weights/best.pt** within the folder.

## Video Walkthrough

For an overview and walkthrough, watch the video [here](https://drive.google.com/file/d/1KVXE3TM1fPOUze0YBhTB7XIHOSySholn/view?usp=sharing).
