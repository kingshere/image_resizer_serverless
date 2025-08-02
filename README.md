# 🖼️ Serverless Image Resizer using AWS Lambda & S3  
*A fully serverless image processing pipeline on AWS*

---

## 🚀 Overview

This project automates image resizing using a **serverless architecture** powered by AWS Lambda and S3. When an image is uploaded to a source S3 bucket, it automatically triggers a Lambda function that resizes the image and stores the output in a destination bucket.


---

## ✨ Features

- ✅ Serverless: Fully event-driven using AWS Lambda.
- 📁 S3 Triggers: Monitors a source bucket for image uploads.
- 🧠 Smart Processing: Resizes images using the **Pillow** Python library.
- 🧺 Output: Stores resized images in a separate destination bucket.
- 📊 Monitoring: CloudWatch logs for easy debugging and tracking.

---

## 🧰 Tech Stack

| Component            | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| **AWS S3**           | Stores original and resized images in separate buckets                  |
| **AWS Lambda**       | Executes the image resizing logic on each upload                        |
| **AWS CloudWatch**   | Logs execution details, errors, and performance metrics                 |
| **Pillow (PIL)**     | Python image processing library used to resize images                   |

---
