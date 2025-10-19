## Malaria Parasite Detection with YOLOv5

This project presents a deep learning pipeline using **YOLOv5** for the **real-time detection of malaria parasites** from blood smear images. The model was trained and tuned on a curated microscopy dataset to assist in early, automated screening for malaria in low-resource clinical settings. By combining **computer vision**, **embedded AI**, and **model optimization**, this work demonstrates how deep learning can contribute to accessible healthcare diagnostics.

## Overview

The repository includes the full workflow — from dataset preparation and model training to evaluation, deployment, and performance benchmarking on embedded devices.  
The model achieves:

- **mAP@0.5:** 0.98  
- **mAP@[0.5:0.95]:** 0.70  
- **Model size reduction:** 45%  
- **GPU memory reduction:** 30%  
- **Inference speed:** 5 FPS on Raspberry Pi 5 (768×768 input)

Performance remains consistent across variations in staining and microscope conditions.

---

