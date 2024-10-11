## OpenKMAP

**KMAP (Kinetic Modeling and Analysis Package)** offers a collection of C/C++ source code and wrapper functions designed to implement and apply different tracer kinetic models for analyzing dynamic positron emission tomography (PET) data, particularly in response to the challenges emerging in total-body PET kinetic modeling. The package was originally developed at the University of California, Davis. **OpenKMAP** is its open-source version. The primary objective of this open-source package is to share tracer kinetic modeling techniques and offer kinetic modeling developers a foundation to build upon without starting from scratch. 

<img align="left" src="https://github.com/user-attachments/assets/dc93ccfc-7ab0-4cde-b3f4-aeabd3562033" width="400" >

As part of **OpenKMAP**, two key packages are currently provided:

- **[KMAP-C](https://github.com/OpenKMI/C-KMAP):** A C/C++ toolkit that provides a suite of routines for implementing various tracer kinetic models. These include source code and MEX files that enable integration with other software, such as MATLAB.
  
- **[KMAP-M](https://github.com/OpenKMI/M-KMAP):** A MATLAB toolbox built on top of KMAP-C. This toolbox provides a user-friendly interface for performing kinetic modeling and analysis using MATLAB, with support for multiple operating systems including Windows, Linux, and macOS.

Together, KMAP-C and KMAP-M offer a solution for researchers in tracer kinetic modeling, providing both the low-level computational tools and the high-level MATLAB functionality.

>[!NOTE]
>**Ongoing Effort**: Both KMAP-C and KMAP-M are continually being updated. The development team is working on adding new models, optimizing performance, and expanding the functionality. **These packages are provided “as is” without warranty**, but contributions from the community are highly encouraged to improve and expand the tools.

## OpenIFun

<img align="right" src="https://github.com/user-attachments/assets/73174ebe-ea61-40b7-b400-256d85dbbc41" width="200" >

**[OpenIFun](https://github.com/OpenKMI/OpenIFun)** is an open-data project aiming to build a database of blood input functions for tracer kinetic modeling of dynamic PET data. The first effort focuses on using total-body PET scanners to acquire image-derived input functions (IDIF) from major blood pools and plans to collect from dynamic FDG-PET scans of 200 human subjects across multiple institutions.

## Contributing
We welcome contributions from the community! Whether you’d like to suggest improvements, report bugs, or contribute code, we encourage you to get involved. Please refer to the contribution guidelines in each repository for more details.

