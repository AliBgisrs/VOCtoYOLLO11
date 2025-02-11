Description:
Tool Name: Convert VOC to YOLO

Description: This tool is designed to convert a PASCAL VOC dataset into the YOLO format while preserving the original PNG images. The tool allows users to perform dataset splitting for training and validation sets based on a user-defined split ratio. It processes XML annotations, converts them to the YOLO format, and organizes the dataset into directories suitable for YOLO training. Additionally, the tool generates a data.yaml file required by YOLO for model training. It is specifically useful for users who want to use PASCAL VOC formatted datasets for training YOLO-based object detection models.



Key Features:
Converts PASCAL VOC dataset annotations to YOLO format.
Supports dataset splitting (train/validation) with a user-defined split ratio.
Organizes images and annotations into YOLO-compatible directories.
Generates the required data.yaml file for YOLO training.
Can handle single-class datasets (e.g., class '0').


Input:
PASCAL VOC formatted dataset folder containing images and XML annotations.
Output:
YOLO formatted dataset with images and labels organized into train and validation directories.
data.yaml file for YOLO model configuration.


Tags:
PASCAL VOC: The input dataset format for the tool.
YOLO: The output format for the tool.
Dataset Conversion: Conversion of datasets between different formats.
Data Splitting: Dividing the dataset into training and validation sets.
Deep Learning: Used for preparing datasets for deep learning models.
Image Annotation: Converts image annotations from VOC XML format to YOLO text format.
Machine Learning: Preparing datasets for object detection using YOLO.


Additional Information:
The tool assumes a single-class dataset for simplicity, with class 0 hardcoded. Users with multi-class datasets may need to modify the class handling logic.
The tool can be run from ArcGIS Pro, and it organizes the dataset in a way that is directly usable for YOLO-based object detection training.


How to Use:
Input the folder containing the PASCAL VOC dataset (images and XML annotations).
Define the output folder where the YOLO dataset will be saved.
Set the validation split ratio (a value between 0 and 1).
Run the tool, and it will generate the YOLO-compatible dataset and configuration files.
