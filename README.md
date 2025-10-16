# 🧠 Edge Detection in Real-World Applications (OpenCV + Python)

This repository demonstrates **five real-world examples** of edge detection using **OpenCV** in **Python** — each visualizing all three major edge detection techniques:

- **Sobel Operator** (Gradient-based edge detection)
- **Laplacian Operator** (Second-order derivative)
- **Canny Edge Detector** (Advanced multi-stage detection)

The project is designed for **Google Colab**, with built-in image upload support.

---

## 📸 Overview

Edge detection is a core concept in computer vision. It helps identify object boundaries, patterns, and shapes in an image.  
This repository shows practical examples across different real-world domains.

---

## ⚙️ Techniques Used

| Technique | Description |
|------------|--------------|
| **Sobel** | Detects intensity gradients in horizontal and vertical directions. |
| **Laplacian** | Uses second derivatives to find edges, sensitive to noise. |
| **Canny** | Multi-stage process with noise reduction, gradient detection, and thresholding. |

---

## 💡 Real-World Examples

| # | Application | Description | File |
|---|--------------|--------------|------|
| 1️⃣ | **Lane Detection (Autonomous Vehicles)** | Detects road lane boundaries from dash-cam or aerial images. | `example_1_lane_detection.ipynb` |
| 2️⃣ | **Medical Imaging (X-ray / MRI)** | Highlights edges of bones or organs in grayscale scans. | `example_2_medical_imaging.ipynb` |
| 3️⃣ | **Industrial Quality Inspection** | Detects cracks, scratches, or irregularities on manufactured surfaces. | `example_3_industrial_inspection.ipynb` |
| 4️⃣ | **Document Edge Detection (OCR Preprocessing)** | Finds page or text region boundaries before OCR. | `example_4_document_ocr.ipynb` |
| 5️⃣ | **Object Recognition / Counting (Fruits Example)** | Detects object outlines for segmentation or counting tasks. | `example_5_object_detection.ipynb` |

---

## 🧩 Example Output

Each notebook displays four side-by-side images:
1. Original Image  
2. Sobel Edge Map  
3. Laplacian Edge Map  
4. Canny Edge Map  

Example layout:

