# LiDAR-Person-Dataset-LogicTronix

This repository contains a LiDAR dataset focused on pedestrian (person) detection, recorded and processed by LogicTronix. The dataset consists of 3D point cloud data collected using the Velodyne VLP-16 Puck sensor, converted into different formats, and labeled for machine learning applications.

## LOGICTRONIX_ENVIROMENT_PCD_DATASET_PCD

- Contains raw 3D point cloud data recorded in front of the LogicTronix building.
- Files are stored in .pcd format.
- Includes randomly selected high-quality samples from the recorded environment.

## LOGICTRONIX_ENVIROMENT_PCD_DATASET_BIN

- Contains .bin format conversions of the corresponding .pcd files.
- Converted using the pcd2bin GitHub repository https://github.com/Yuseung-Na/pcd2bin

## LOGICTRONIX_ENVIROMENT_PCD_DATASET_LABELED

- Contains labeled data for pedestrian (person) of respective .bin point cloud datas.
- Labeled using the 3D-LiDAR-annotator https://github.com/songanz/3D-LiDAR-annotator
- Generates 2D and 3D bounding boxes efficiently.
- Labeled annotations are stored in .json format.

## Usage

- The .pcd files provide raw point cloud data for preprocessing and analysis.
- The .bin files are suitable for deep learning frameworks requiring binary input.
- The .json annotation files offer structured labeled data for supervised learning.
