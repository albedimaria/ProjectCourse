# Wave Digital Filter Implementation of linear and nonlinear audio circuits on Eventide H9000

The Eventide H9000 is a multi-effects processor hardware with an integrated visual software, VSig3, that enables the creation of custom algorithms. This solution combines the efficiency of a hardware with the properties of designing algorithms by the software. VSig3's language allows also the creation of low-level algorithms, although there are not any example in the literature.
In this paper we show on how to model linear and nonlinear audio circuits with the Wave Digital Filters (WDFs) method, in the VSig3 platform. In particular, to deal with nonlinearities the Canonical PieceWise-Linear (CPWL) representation is adopted. Both WDF and CPWL exhibit highly desirable properties that perfectly match the possibilities offered by the VSig3's language.
Practically, we present the steps of the first successful implementation ever done of an WDFs-based algorithm on H9000.
At last, we will show a diodes clipper circuits as an example of application, in order to verify the validity of the proposed method.

Softwares: Matlab, VSig3.
Hardware: Eventide H9000.
