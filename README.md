## ShareKMAP

**KMAP (Kinetic Modeling and Analysis Package)** offers a collection of C/C++ source code and wrapper functions designed to implement and apply different tracer kinetic models for analyzing dynamic positron emission tomography (PET) data, particularly in response to the challenges emerging in total-body PET kinetic modeling. The package was originally developed at the University of California, Davis. Its open-source version, **ShareKMAP**, was launched to support the [Open Kinetic Modeling Initiative](https://www.openkmi.org/). The primary objective of this open-source package is to share tracer kinetic modeling techniques and offer kinetic modeling developers a foundation to build upon without starting from scratch. 

<img align="left" src="https://github.com/user-attachments/assets/de27a25f-88da-4b0f-beb5-6b3c2570a878" width="400" >

As part of the open-source **ShareKMAP**, two key packages are currently provided:

- **[KMAP-C](https://github.com/openkmi/KMAP-C):** A C/C++ toolkit that provides a suite of routines for implementing various tracer kinetic models. These include source code and MEX files that enable integration with other software, such as MATLAB.
  
- **[KMAP-M](https://github.com/openkmi/KMAP-M):** A MATLAB toolbox built on top of OpenKMAP-C. This toolbox provides an interface for performing kinetic modeling and analysis using MATLAB, supporting multiple operating systems including Windows, Linux, and macOS.

Together, KMAP-C and KMAP-M offer a solution for researchers in tracer kinetic modeling, providing both the low-level computational tools and the high-level MATLAB functionality.

>[!WARNING]
>The **KMAP** packages offer open-source code to disseminate basic and advanced tracer kinetic modeling approaches in a timely matter. These packages are not intended to serve as a comprehensive and user-friendly software solution for end users. For those seeking an all-encompassing solution, commercial software like PMOD may be a better option.
>
>Both KMAP-C and KMAP-M are continually being updated. The development team is working on adding new models, optimizing performance, and expanding the functionality. These packages are provided “as is” without warranty. The shared modeling code may also only reflect the research interests of a very limited number of groups. 

## Contributing
We welcome contributions from the community! Whether you’d like to suggest improvements, report bugs, or contribute code, we encourage you to get involved. Please refer to the contribution guidelines in each repository for more details.

