# Yolo-v8-annotation

# 🎯 YOLO Object Detection Annotation Project

This project focuses on preparing datasets for training **YOLO (You Only Look Once)** models for object detection tasks.

---

## 🧠 What Is YOLO Annotation?

YOLO requires each object in an image to be **annotated** with:

- 🏷️ **Class label**: The category or type of the object (e.g., person, car, dog).
- 📦 **Bounding box**: The location of the object in the image, specified using:
  - `x_center` (normalized between 0 and 1)
  - `y_center` (normalized)
  - `width` (normalized)
  - `height` (normalized)

---

## 🗂️ Annotation Format

Annotations are saved in **`.txt` files** that match the image filenames, using the following YOLO format:

