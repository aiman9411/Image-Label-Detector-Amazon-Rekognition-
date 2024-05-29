
# Image Label Detector using Amazon Rekognition

## Overview

This project demonstrates how to create an image label detector using Amazon Rekognition and Amazon S3. Images are uploaded to an S3 bucket, and the Amazon Rekognition API is used to analyze these images and return labels.

## Features

- Upload images to Amazon S3.
- Use Amazon Rekognition to detect and label objects in the images.
- Retrieve and display image labels.

## Prerequisites

Before you begin, ensure you have the following:

- AWS Account: You need an AWS account to use Amazon S3 and Amazon Rekognition.
- AWS CLI: Installed and configured with appropriate permissions.
- Python: Installed on your machine (preferably Python 3.x).
- Boto3: AWS SDK for Python. Install using pip install boto3.

## Usage

1. **Upload an image to S3**.
2. **Run the script**:
    ```bash
    python image_label_detector.py
    ```
    Update `bucket` and `key` in the script with your S3 bucket name and image filename.
