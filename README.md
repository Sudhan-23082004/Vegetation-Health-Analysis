# 🌿 Vegetation Health Analysis using UAV Remote Sensing

> **Project Title:** Vegetation Health Analysis Using UAV Remote Sensing  
> **Developed By:** Sudhan R  
> **Guided By:** Dr. Pradesh Jena  
> **Institution:** North Eastern Space Applications Centre (NESAC), ISRO  
> **Training Program:** *UAV Remote Sensing: Technological Advances and its Applications (2024)*  
> **Department:** Computer Science and Engineering, Sri Eshwar College of Engineering  
> **Domains:** Remote Sensing · Precision Agriculture · UAV Imaging  
> **Technologies Used:** UAV | Pix4D | QGIS | Tableau | Mission Planner  

---

## 📌 Overview

This project leverages Unmanned Aerial Vehicles (UAVs) and spectral imaging techniques to analyze vegetation health for agricultural monitoring. By calculating **Normalized Difference Vegetation Index (NDVI)** and **Normalized Difference Red Edge (NDRE)** using multispectral UAV imagery, we detect and visualize plant stress levels and identify cropped vs. non-cropped zones.

The project eliminates the need for time-consuming manual field surveys and provides an efficient, data-driven approach to precision farming.

---

## 📖 Table of Contents

1. [Abstract](#abstract)
2. [Problem Statement](#problem-statement)
3. [Tools & Technologies](#tools--technologies)
4. [Methodology](#methodology)
5. [Results & Visualizations](#results--visualizations)
6. [Project Structure](#project-structure)
7. [Outcome](#outcome)
8. [Future Scope](#future-scope)
9. [Credits](#credits)

---

## 🧠 Abstract

Efficient monitoring of crop health is crucial in precision agriculture to optimize yield and sustainability. This project utilizes UAV-based remote sensing with spectral indices like NDVI and NDRE to assess vegetation stress. High-resolution images were processed through Pix4D and analyzed in QGIS to classify cropped areas and determine vegetation health. The outcomes were visualized using Tableau, offering a robust, real-time monitoring solution that reduces manual error and improves decision-making in agriculture.

---

## 🚩 Problem Statement

Traditional methods such as manual field surveys are labor-intensive, subjective, and often inaccurate. Satellite-based methods, while broad in scope, lack the resolution needed for precise field-level monitoring. This project addresses:

- Lack of real-time monitoring
- Low spatial resolution in satellite data
- Inaccurate manual assessment methods
- Absence of data-driven insights for decision-making

---

## 🛠️ Tools & Technologies

| Tool              | Purpose                                      |
|-------------------|----------------------------------------------|
| **Mission Planner**  | UAV flight path planning                    |
| **Pix4D**             | Image stitching, DSM, and orthomosaic generation |
| **QGIS**              | NDVI / NDRE layer generation and GIS analysis |
| **Tableau**           | Visualizing stress maps and dashboards     |
| **Multispectral Camera** | Capturing high-resolution UAV images       |

---

## 🔍 Methodology

### 1. UAV Flight Planning
- Designed flight paths and waypoints using **Mission Planner**
- Ensured optimal altitude and coverage for agricultural plots

### 2. Image Acquisition
- Captured multispectral aerial imagery using UAV-mounted sensors
- Ensured overlap and consistency for Pix4D stitching

### 3. Image Processing (Pix4D)
- Generated **Orthomosaic images** and **Digital Surface Models (DSM)**
- Exported for GIS analysis

### 4. Vegetation Health Analysis (QGIS)
- Computed **NDVI**: Identified healthy vs. unhealthy zones  
  `NDVI = (NIR - Red) / (NIR + Red)`
- Computed **NDRE**: Mapped crop stress levels  
  `NDRE = (NIR - RedEdge) / (NIR + RedEdge)`
- Applied thresholds:
  - NDVI ≥ 0.35: Cropped zones
  - NDRE: Low, Medium, High stress classes

### 5. Visualization (Tableau)
- Built interactive dashboards showing:
  - Cropped and non-cropped areas
  - Crop stress classification
  - Vegetation index distribution

---

## 📊 Results & Visualizations

| Output Type              | Description                            |
|--------------------------|----------------------------------------|
| NDVI Map                 | Cropped zone classification            |
| NDRE Map                 | Crop stress levels (Low/Medium/High)   |
| Tableau Dashboard        | Visualization of vegetation health     |
| DSM (Digital Surface Model) | Elevation-based analysis             |

> Screenshots and maps can be found in the `images/` folder.

---

## 📁 Project Structure

```bash
UAV-Vegetation-Health/
├── 📁 Output/                         # Final processed outputs (NDVI, NDRE maps)
├── 📁 Picture/                        # UAV field images taken at NESAC
├── 📄 reclassified_ndvi23_10.qgz     # QGIS project file with NDVI layer
├── 📄 Template Agricultural Application.pptx  # Project PPT
├── 📄 README.md                      # Project documentation (you are here)
├── 📄 LICENSE                        # License file
```
---

## ✅ Outcome

- Replaced manual surveying with automated analysis  
- Achieved accurate crop stress detection via **NDVI** and **NDRE**  
- Created an easy-to-interpret **decision support system**  
- Promoted **sustainable agricultural practices** using real-time insights  

---

## 🚀 Future Scope

- Integration of **Machine Learning** models for predictive analytics  
- Deployment of **real-time monitoring systems** using edge computing  
- Expansion to **multi-seasonal crop monitoring** for yield forecasting  
- Incorporation of **UAV LiDAR** and **hyperspectral imaging** for advanced analysis  

---

## 👨‍💻 Credits

- **Project Title:** Vegetation Health Analysis Using UAV Remote Sensing  
- **Developed By:** Sudhan R  
- **Guided By:** Dr. Pradesh Jena  
- **Institution:** North Eastern Space Applications Centre (NESAC), ISRO  
- **Training Program:** *UAV Remote Sensing: Technological Advances and its Applications (2024)*  
- **Department:** Computer Science and Engineering, Sri Eshwar College of Engineering  
- **Domains:** Remote Sensing · Precision Agriculture · UAV Imaging  
- **Technologies Used:** UAV | Pix4D | QGIS | Tableau | Mission Planner  
