
# ANN_Project_2_GroupB_AI_6A1

## Semester Project

## Pakistani Politician Image Classifier

**Project 2 — CNN Image Classification**
**Comparative Study: VGG-16, ResNet-50, EfficientNet-B0**

## Authors

Noor ul Huda, Khushbakht Adnan, Urwa Tehseen, Zeenat Ijaz

---

## Project Overview

This project implements a CNN-based image classification system to identify 16 Pakistani politicians using transfer learning models: VGG-16, ResNet-50, and EfficientNet-B0. A custom dataset was created using web scraping, followed by preprocessing, training, and performance comparison.

---

## Key Features

* 16-class image classification
* VGG-16, ResNet-50, EfficientNet-B0 models
* Transfer learning with ImageNet weights
* Web scraping using Selenium
* Data cleaning and deduplication
* Gradio-based interface
* Real-time prediction with confidence scores

---

## Results

* Best Model: ResNet-50
* Accuracy: 94.93%
* Validation Accuracy: 97.00%
* F1 Score: 0.9488

---

## Technologies Used

Python, PyTorch, TensorFlow/Keras, Selenium, OpenCV, Gradio, Google Colab, ImageHash

---

## Dataset

* 16 classes
* 1331 images
* Collected via Bing Image Search
* Cleaned using perceptual hashing

---

## Pipeline

Data Collection → Cleaning → Preprocessing → Training → Evaluation → Deployment

---

## Conclusion

ResNet-50 performed best due to its residual learning structure, making it most suitable for this classification task.

---

## Future Work

* Expand dataset
* Add face detection (MTCNN/RetinaFace)
* Use Vision Transformers
* Improve deployment performance

---

