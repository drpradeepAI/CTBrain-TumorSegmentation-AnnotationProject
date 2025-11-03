# 🧠 MRI Brain Tumor Segmentation — Annotation Project  

A curated dataset of **50 MRI brain scans** annotated for **tumor segmentation** using **CVAT**.  
This project demonstrates a structured **medical computer vision annotation pipeline** — ready for **AI model training, validation, and educational research**.

---

## 📘 Overview

| **Attribute** | **Description** |
|----------------|----------------|
| **Modality** | MRI (Magnetic Resonance Imaging) |
| **Region of Interest** | Brain |
| **Condition** | Brain Tumor (normal and abnormal cases included) |
| **Dataset Size** | 50 MRI images |
| **Annotation Tool** | [CVAT – Computer Vision Annotation Tool](https://cvat.org/) |
| **Annotation Type** | Polygonal + Mask Segmentation |
| **Segmentation Classes** | `tumor`, `background` |
| **Export Formats** | COCO JSON, Pascal VOC XML, PNG Masks |
| **Resolution** | 512 × 512 px |
| **Color Mode** | Grayscale |
| **Purpose** | AI model development, benchmarking, and education |

---

## 📁 Folder Structure

50_mri_brain_tumor_annotation_project/
├── raw_data/ # Original MRI brain scans (unannotated)
├── annotated_data/ # Labeled annotations (COCO, YOLO, XML, PNG)
├── metadata/ # Schema files, mappings, and dataset info
├── screenshots/ # Workflow documentation (PDFs, PNGs)
└── README.md # Current documentation file

---

## 🩺 Folder Descriptions

### 🧠 `raw_data/`
Contains 50 unannotated MRI brain scans — both normal and tumor-affected cases.  
➡️ [View Raw Data](./raw_data)

---

### 🎯 `annotated_data/`
Includes multi-format annotations compatible with major AI frameworks:  
- **COCO JSON** → PyTorch, Detectron2  
- **YOLO TXT** → YOLOv5–YOLOv8  
- **CVAT XML** → Re-importable into CVAT  
- **PNG Masks** → Pixel-wise tumor segmentation maps  

➡️ [View Annotated Data](./annotated_data)

---

### 🧾 `metadata/`
Holds dataset-level descriptors, mappings, and placeholders for schema versioning.  
➡️ [View Metadata](./metadata)

---

### 🖼️ `screenshots/`
Contains project documentation — raw data samples, annotations, and workflow visuals.  
➡️ [View Screenshots](./screenshots)

---

## ⚙️ Data Workflow Summary

| **Step** | **Description** |
|-----------|----------------|
| **1. Data Preparation** | MRI brain scans curated and preprocessed for consistency |
| **2. Annotation (CVAT)** | Manual polygon + mask-based segmentation |
| **3. Exporting Formats** | COCO JSON, Pascal VOC XML, and PNG masks |
| **4. Documentation** | Screenshots and workflow visual proof |
| **5. Validation** | Visual QA and format verification |

---

## 🧠 Applications

- Tumor segmentation and boundary localization  
- AI model training with MONAI, U-Net, and DeepLab  
- Medical imaging workflow demonstrations  
- Freelance dataset showcase and medical AI portfolio projects  
- Educational use in annotation and segmentation tutorials  

---

## 🧰 Recommended Tools

| **Task** | **Recommended Tools** |
|-----------|----------------------|
| **Annotation** | CVAT, ITK-SNAP, 3D Slicer |
| **Visualization** | FiftyOne, matplotlib, Roboflow |
| **Model Training** | MONAI, U-Net, Detectron2 |
| **Evaluation Metrics** | Dice, IoU, Hausdorff Distance |

---

## 🧩 Compatibility

| **Framework** | **Supported Format** | **Folder** |
|----------------|----------------------|-------------|
| **PyTorch / Detectron2** | COCO JSON | `annotated_data/COCO` |
| **YOLOv5–YOLOv8** | YOLO TXT | `annotated_data/YOLO` |
| **CVAT** | XML | `annotated_data/cvat_xml` |
| **MONAI / U-Net** | PNG Masks | `annotated_data/segmentation_masks` |

---

## 📜 License

Licensed under the **MIT License**.  
© 2025 **Dr. Pradeep Shanmugam** — *MedDataForAI (Udyam Registered MSME, Government of India)*

---

## 🔖 Citation (APA Style)

> **Shanmugam, P.** (2025). *MRI Brain Tumor Segmentation — Medical AI Data Annotation Project (v1.0).*  
> MedDataForAI (Udyam Registered MSME, Government of India).  
> Available at: [https://github.com/drpradeepAI/MRIBrain-TumorSegmentation-AnnotationProject](https://github.com/drpradeepAI/MRIBrain-TumorSegmentation-AnnotationProject)

---

## 🧾 Version Control

| **Version** | **Date** | **Description** |
|--------------|-----------|----------------|
| **1.0** | 2025-11 | Initial release with 50 MRI brain images and multi-format annotations |
| **1.1 (Planned)** | 2026-Q1 | Add extended metadata and refined COCO-style masks |

---

✨ *A MedDataForAI project — structured for research reproducibility, educational clarity, and freelance presentation.*
