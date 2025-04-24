# 🌍 EuroSAT RGB Dataset  
_A Novel Dataset and Deep Learning Benchmark for Land Use and Land Cover Classification_

EuroSAT is a land use and land cover (LULC) classification dataset based on Sentinel-2 satellite imagery. It contains 27,000 labeled and geo-referenced images distributed across **10 distinct classes**, making it ideal for training deep learning models in remote sensing and land cover classification tasks.

## 📦 Dataset Overview

- **Source**: Sentinel-2 Satellite (13 spectral bands)
- **Version**: This repository contains the **RGB version** with only the R, G, and B frequency bands
- **Format**: JPEG images
- **Total Images**: 27,000
- **Image Size**: 64x64 pixels (standard resizing used in many CNN-based studies)
- **Classes** (≈2,500 images per class):
  - Annual Crop  
  - Forest  
  - Herbaceous Vegetation  
  - Highway  
  - Industrial  
  - Pasture  
  - Permanent Crop  
  - Residential  
  - River  
  - Sea or Lake  

## 📂 Folder Structure

The dataset is organized into class-specific subfolders:

EuroSAT_RGB/ ├── AnnualCrop/ ├── Forest/ ├── HerbaceousVegetation/ ├── Highway/ ├── Industrial/ ├── Pasture/ ├── PermanentCrop/ ├── Residential/ ├── River/ └── SeaLake/
