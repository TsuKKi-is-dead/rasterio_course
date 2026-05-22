# rasterio_course

This repo represenst my learning experience of learning RasterIO and all its background tools

# RasterIO Course Setup and Learning Journey

## Overview

This repository documents my learning journey while studying RasterIO and geospatial image processing.

The goal of this course is to:

- Learn raster data handling
- Understand geospatial image processing
- Work with GeoTIFF and satellite imagery
- Learn RasterIO fundamentals
- Build a proper Python GIS development environment

---

# Course Repository

Repository used during learning:

```bash
git clone https://github.com/TsuKKi-is-dead/rasterio_course.git
```

---

# Development Environment

## Editor

- Visual Studio Code

## Environment

- Python Virtual Environment (venv)

## Operating System

- macOS

---

# Environment Setup

## Create Virtual Environment

```bash
python3 -m venv venv
```

## Activate Environment

```bash
source venv/bin/activate
```

## Install Required Libraries

```bash
pip install rasterio geopandas shapely fiona pyproj jupyter matplotlib numpy pandas
```

---

# Requirements File

## requirements.txt

```txt
rasterio==1.4.3
geopandas==1.1.1
shapely==2.1.1
fiona==1.10.1
pyproj==3.7.2

numpy==2.3.2
pandas==2.3.1
matplotlib==3.10.5

jupyter==1.1.1
ipykernel==6.30.1
```

Install using:

```bash
pip install -r requirements.txt
```

---

# Environment Verification

## Check Python Environment

```bash
which python
which pip
```

Both should point to the virtual environment.

---

## Verify GIS Libraries

```bash
python -c "import rasterio, geopandas, shapely, fiona, pyproj, numpy, pandas, matplotlib; print('ALL GIS LIBS WORKING')"
```

---

## Verify RasterIO

```bash
python -c "import rasterio; print(rasterio.__version__)"
```

---

## Verify GDAL Backend

```bash
python -c "import rasterio; print(rasterio.__gdal_version__)"
```

---

## Verify GeoPandas

```bash
python -c "import geopandas as gpd; print(gpd.__version__)"
```

---

## Verify Jupyter

```bash
jupyter --version
```

---

# VS Code Setup

## Select Python Interpreter

Inside VS Code:

```text
Cmd + Shift + P
→ Python: Select Interpreter
→ Select ./venv/bin/python
```

---

# Recommended VS Code Extensions

- Python
- Jupyter
- Pylance
- Geo Data Viewer
- Rainbow CSV

---

# Folder Structure

```text
rasterio_course/
│
├── venv/
├── notebooks/
├── data/
├── outputs/
├── scripts/
├── requirements.txt
└── README.md
```

---

# Topics Covered in the Course

- Raster data basics
- Reading GeoTIFF files
- Raster metadata
- Bands and channels
- Coordinate Reference Systems (CRS)
- Raster transformations
- Windowed reading
- Visualization with Matplotlib
- Basic geospatial workflows

---

# Learning Goals

By the end of the course:

- Understand RasterIO fundamentals
- Work comfortably with raster datasets
- Build geospatial processing workflows
- Understand GDAL-backed raster operations
- Prepare for advanced remote sensing and satellite image analysis

---

# Notes

This repository serves as a documented learning environment for practicing RasterIO, geospatial image processing, and raster-based workflows using Python.
