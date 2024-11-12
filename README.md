## OpenKMAP

**KMAP (Kinetic Modeling and Analysis Package)** offers a collection of C/C++ source code and wrapper functions designed to implement and apply different tracer kinetic models for analyzing dynamic positron emission tomography (PET) data, particularly in response to the challenges emerging in total-body PET kinetic modeling. The package was originally developed at the University of California, Davis. Its open-source version, **OpenKMAP**, was launched to support the [Open Kinetic Modeling Initiative](https://www.openkmi.org/). The primary objective of this open-source package is to share tracer kinetic modeling techniques and offer kinetic modeling developers a foundation to build upon without starting from scratch. 

<img align="left" src="https://github.com/user-attachments/assets/dc93ccfc-7ab0-4cde-b3f4-aeabd3562033" width="400" >

As part of **OpenKMAP**, two key packages are currently provided:

- **[KMAP-C](https://github.com/openkmi/KMAP-C):** A C/C++ toolkit that provides a suite of routines for implementing various tracer kinetic models. These include source code and MEX files that enable integration with other software, such as MATLAB.
  
- **[KMAP-M](https://github.com/openkmi/KMAP-M):** A MATLAB toolbox built on top of OpenKMAP-C. This toolbox provides a user-friendly interface for performing kinetic modeling and analysis using MATLAB, with support for multiple operating systems including Windows, Linux, and macOS.

Together, KMAP-C and KMAP-M offer a solution for researchers in tracer kinetic modeling, providing both the low-level computational tools and the high-level MATLAB functionality.

>[!WARNING]
>The OpenKMAP packages offer open-source code to disseminate both basic and advanced kinetic modeling approaches in a timely matter. The packages do not aim to provide a comprehensive software solution. Commercial software may provide a better solution for end users.
>
>Both KMAP-C and KMAP-M are continually being updated. The development team is working on adding new models, optimizing performance, and expanding the functionality. **These packages are provided “as is” without warranty**, but contributions from the community are highly encouraged to improve and expand the tools.

## Contributing
We welcome contributions from the community! Whether you’d like to suggest improvements, report bugs, or contribute code, we encourage you to get involved. Please refer to the contribution guidelines in each repository for more details.

