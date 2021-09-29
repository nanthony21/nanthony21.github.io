---
title: Projects
description: A Collection of Open-Source Software
---

# A Collection of Open-Source Software

### PWSpy  
This package consists of core code for the purpose of analyzing and interpreting 
Partial Wave Spectroscopic Microscopy (PWS) data. Provides custom data types to
make extracting useful information from raw microscopy data easy.
Includes a wide range of utilities for computer vision, parallel computation, segmentation, etc.  
[Documentation](https://pwspy.readthedocs.io/en/dev/)  
[Repository](https://github.com/nanthony21/PWSpy)

### PWSPy_gui
A collection of GUI applications built on top of the `PWSpy` Python package making the analysis of PWS 
data easy and accessible to all.  

 - *PWS Analysis*: Used for drawing ROIs, running standard data analysis routines, visualizing hyperspectral image cubes, and tabifying results.  
 - *ER Creator*: Processes measurements of reference reflections (Materials with known RI) into an `ExtraReflectance` calibration file. This file is used by `PWSpy` to convert raw data into accurate reflectometry results.
 
[Repository](https://github.com/nanthony21/pwspy_gui)  
[Tutorial Video](AnalysisIntroduction/demo.html)  

### mpl_qt_viz
This package consists of UI extensions to the Matplotlib plotting library built using PyQt5.
It includes interactive Qt widgets to view N-Dimensional images, conveniently cluster plots into a dockable window,
provide various modes of user-friendly ROI drawing, semi-automated segmentation, and more.  
[Documentation](https://mpl-qt-viz.readthedocs.io/en/latest/)  
[Repository](https://github.com/nanthony21/mpl_qt_viz)

### PWS Acquisition Plugin
A collection of plugins for Micro-Manager to provide automated acquisition of
Partial Wave Spectroscopic Microscopy (PWS), PWS Dynamics, and fluorescence images.
A tree based acquisition engine in addition to an enhanced hardware abstraction layer enable
reliable imaging with complex acquisition routines.
[Repository](https://github.com/nanthony21/mmPWSPlugin)

### Calibration Suite
This PyQt GUI connects to the `PWS Acquisition Plugin` via a [Py4J](https://www.py4j.org/) in order to automate
the various routine measurements taken to ensure stable calibration of hyperspectral PWS microscopes.
[Repository](https://github.com/nanthony21/PWSCalibrationSuite)

### PWS Micro-Manager
A customized fork of the popular open-source microscope automation software tailored to the needs
of data acquisition for PWS related experiments.  
[Repository](https://github.com/nanthony21/PWSMicroManager)


