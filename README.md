# SAM2-Based Object Detection for Product Images

## Overview

This repository contains an implementation of object detection using the Segment Anything Model 2 (SAM2) for product images. The current implementation focuses on detecting 'can_chowder' objects as a proof of concept.
## Key Features:
- Utilizes SAM2 from Hugging Face for mask generation
- Converts masks to bounding boxes for object detection
- Includes visualization of results and performance metrics
- Demonstrates the use of the SAM2 large model

This project was developed as part of a timed coding challenge, showcasing rapid prototyping and decision-making under constraints. While currently limited to one product type, the framework is designed for easy expansion to multiple object categories.

Tech Stack: **Python, PyTorch, OpenCV, Matplotlib, Hugging Face Transformers**

>***Note***: This is a work in progress. Future improvements include expanding to more object types, optimizing performance, and enhancing evaluation metrics.

**Output:**
![image](https://github.com/user-attachments/assets/fcbf9092-1b53-42e4-94a7-7373a4f39fdc)
![image](https://github.com/user-attachments/assets/d2048a95-1388-4e65-94b7-6f95be71a4fc)
