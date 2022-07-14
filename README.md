# Wave Digital Filter Implementation of linear and nonlinear audio circuits on Eventide H9000

The Eventide H9000 is a multi-effects processor hardware with an
integrated visual software, VSig3, that enables the creation of custom algorithms. This solution combines the efficiency of a hard-
ware with the properties of designing algorithms by the software.
VSig3’s language allows also the creation of low-level algorithms,
although there are not any example in the literature. In this paper we show how to model linear and nonlinear audio circuits with
the Wave Digital Filters (WDFs) method, in the VSig3 platform.
In particular, to deal with nonlinearities, the Canonical PieceWise-Linear (CPWL) representation is adopted. Both WDFs and CPWL
exhibit highly desirable properties that perfectly match the possibilities offered by the VSig3, even considering the language’s lim-
itations, which will be presented. We will show the steps of the
first successful implementation ever done of a WDFs-based algorithm on H9000 and, at last, a diode clipper circuit as an example of
application, in order to verify the validity of the proposed method.

Index Terms: Wave Digital Filters, VSig3, linear and nonlinear audio circuits, Eventide H9000.

Softwares: Matlab, VSig3

Hardware: Eventide H9000

***

## To download: getting started

*VSig3 is only available for H9000 or H9000R owners, and will only be visible on the H9000 installers page (Requires H9000 registration).*

- To run the code, it is required to physically have the H9000 hardware, the Emote software and VSig3 platform
- In order to test the algorithm, first of all it is necessary to match the sampling frequency of the device and the sampling frequency of the H9000. 
- The file of VSig3 has to be loaded in the fx chain of the H9000
- Going to the algorithm section in the interface of H9000, it will be visible the knobs to control the various parameters of the diodes clipper
- It is sufficient to play any record to appreciate the effect of the plugin

***

 ### Platform Compatibility:
 
- Windows 10+
- AAX 64-bit, VST3 64-bit
- macOS 10.11+
- AAX 64-bit, AU 64-bit, VST2 64-bit, VST3 64-bit
- No iLok is required
