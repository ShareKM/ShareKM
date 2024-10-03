# OpenKMI Code and Data Projects

## Overview
The [Open Kinetic Modeling Initiative (OpenKMI)](https://www.openkmi.org/) is an open-source effort aimed at accelerating research and educational opportunities in tracer kinetic modeling for molecular imaging. Tracer kinetic modeling allows for quantitative characterization of molecular processes, such as those involved in cancer and other major diseases. While the field has seen extensive research over the years, its clinical adoption has been limited by technological constraints in PET scanner performance. With advancements such as total-body PET and other long axial field-of-view PET scanners, there is a renewed interest in pushing kinetic modeling forward, and the need for accessible resources has never been greater. OpenKMI seeks to meet this need by offering robust, open-source solutions that make kinetic modeling more accessible to both experienced researchers and newcomers, including Short Courses, Webinars, Open Code, and Open Data. 

## OpenKMAP: An OpenKMI Code Project

One of the ongoing efforts of the initiative, **OpenKMAP**, is to make a set of in-house C/C++ source codes (and their wrappers with other high-level programming languages such as MATLAB) for kinetic modeling and parametric imaging open to kinetic modeling developers. **KMAP (Kinetic Modeling and Analysis Package)** offers a collection of source code and wrapper functions designed to implement and apply different tracer kinetic models for analyzing dynamic positron emission tomography (PET) data, particularly in response to the challenges emerging in total-body PET kinetic modeling. The primary objective of this open-source package is to share tracer kinetic modeling techniques and offer kinetic modeling developers a foundation to build upon without starting from scratch. The package is originally developed at the University of California, Davis. Its open-source version is initiated as a part of the OpenKMI. 
<img align="left" src="https://github.com/user-attachments/assets/51f6aba3-6995-4ce2-a20e-d3f587c274ad" width="500" >

As part of OpenKMAP, two key packages are currently provided:

- **[C-KMAP](https://github.com/OpenKMI/C-KMAP):** A C/C++ toolkit that provides a suite of routines for implementing various tracer kinetic models. These include source code and MEX files that enable integration with other software, such as MATLAB.
  
- **[M-KMAP](https://github.com/OpenKMI/M-KMAP):** A MATLAB toolbox built on top of C-KMAP. This toolbox provides a user-friendly interface for performing kinetic modeling and analysis using MATLAB, with support for multiple operating systems including Windows, Linux, and macOS.

Together, C-KMAP and M-KMAP offer a solution for researchers in tracer kinetic modeling, providing both the low-level computational tools and the high-level MATLAB functionality.

**Ongoing Efforts**: Both packages are continually being updated. The development team is working on adding new models, optimizing performance, and expanding the functionality of both C-KMAP and M-KMAP. The packages are provided “as is” without warranty, but contributions from the community are highly encouraged to improve and expand the tools.

## Contributing
We welcome contributions from the community! Whether you’d like to suggest improvements, report bugs, or contribute code, we encourage you to get involved. Please refer to the contribution guidelines in each repository for more details.

