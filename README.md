ISCo3D
Overview
ISCo3D is a multi-modal dataset designed for 3D object detection tasks in complex real-world environments, specifically focusing on autonomous driving and construction scenarios. The dataset provides synchronized LiDAR point clouds and RGB camera images to support research and development of robust 3D perception algorithms.

Key Features
Multi-Modal Data: Includes high-resolution LiDAR scans and corresponding camera images.

Challenging Environments: Captures both urban driving scenes and dynamic construction sites.

3D Detection Annotations: Provides 3D bounding boxes for a variety of object categories commonly encountered in autonomous driving and construction.

Applications
3D Object Detection

Multi-Modal Sensor Fusion

Autonomous Driving Perception

Robotics in Construction Environments

Dataset Structure
LiDAR/: Raw point cloud data (.bin or .pcd format)

Images/: Calibrated RGB images

Annotations/: 3D bounding box labels in a standard format (e.g., KITTI style or custom JSON)

Calibration/: Sensor calibration files for aligning LiDAR and camera data

Download
You can download the ISCo3D dataset from the following Google Drive link:

Download ISCo3D from Google Drive

Or use gdown to download via command line:

bash
复制
编辑
pip install gdown
gdown https://drive.google.com/uc?id=YOUR_FILE_ID
(Please replace YOUR_FILE_ID with the actual file ID from your Google Drive link.)

Example Visualization
Here is an example of the ISCo3D dataset:


(Make sure to place an example image at assets/example.jpg, or update the link.)

Usage
The dataset can be used to train and evaluate 3D object detection models. Standard frameworks such as MMDetection3D and OpenPCDet can be adapted to work with ISCo3D with minimal modifications.
