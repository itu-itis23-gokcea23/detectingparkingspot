# Human-Level Parking Detection 

This project focuses on identifying parking spot occupancy from a **human-level perspective** (non-bird's eye view). Unlike traditional overhead views, this approach deals with challenges like occlusion, perspective distortion, and varying lighting conditions.

## 🎯 Project Objective
The main goal is to compare and implement state-of-the-art deep learning architectures to detect and segment parking spaces and vehicles in real-world camera angles.

## 🧠 Models Used
We have implemented and evaluated three different architectures:

1.  **YOLOv8:** Used for high-speed object detection (Real-time performance).
2.  **Mask R-CNN:** A classic for instance segmentation to precisely define car and spot boundaries.
3.  **Mask2Former:** A next-generation universal segmentation framework used to achieve state-of-the-art accuracy in complex scenes.
