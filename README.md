# DayOrNight-MinimalProjrct
This project detects whether an image was taken during the day or night using  OpenCV and image processing. It converts the image to the HSV color model and analyzes the V (Value) channel, which represents brightness. If the average brightness is above a threshold, it's classified as day; otherwise, it's night. 🚀🌞🌙

# Day or Night Detection 🌞🌙

This is a simple **image processing** project using **OpenCV** that detects whether an image was taken during the **day** or **night** based on brightness levels.

## 📌 How It Works
- The image is converted from **BGR to HSV** color space.
- The **V (Value)** channel, which represents brightness, is extracted.
- The **mean brightness** is calculated.
- If the brightness is above a threshold, the image is classified as **Day ☀️**; otherwise, it is classified as **Night 🌙**.

## 🚀 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Zahra-Gholami/DayOrNight-MinimalProjrct.git
   cd DayOrNight-MinimalProject

