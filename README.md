# Leveraging SmartNICs for HPC Applications

Tutorial on SmartNICs for International Supercomputing Conference (ISC) 2025

**Held on**: June 13th, 14:00 PM - 18:00 PM [Europe/Berlin]; Hall Y2 - 2nd floor

[Event website and Program](https://isc-hpc.com/program/schedule/)

![BlueField 3 SmartNIC](https://github.com/gt-crnch-rg/smartnic-tutorial-isc25/blob/2c305cbb0ab18d6b76729516c3f65a85b031b7eb/fig/smartnic_bf3.jpg)

## Mentimeter Audience Survey

Please take our survey using [this Mentimeter link]().

## Presenters

* Antonio Peña [(Barcelona Supercomputing Center)](https://www.bsc.es/pena-antonio)
* Jeffrey Young [(Georgia Institute of Technology)](https://jyoung3131.github.io/)
* Richard Graham [(NVIDIA)](https://www.nvidia.com/)
* Oscar Hernandez [(Oak Ridge National Laboratory)](https://www.ornl.gov/)
* Clay Hughes [(Sandia National Laboratories)](https://isc.app.swapcard.com/widget/event/isc-high-performance-2025/person/RXZlbnRQZW9wbGVfMzc5MzA0MTI=)
* Richard Vuduc [(Georgia Institute of Technology)](https://vuduc.org/v2/)
* Aaron Jezghani [(Georgia Institute of Technology)](https://research.gatech.edu/people/aaron-jezghani)


Supporting Contributors:

* Muhammad Usman [(Barcelona Supercomputing Center)](https://www.bsc.es/usman-muhammad)
* Mariano Benito [(Barcelona Supercomputing Center)](https://www.bsc.es)
* Sergio Iserte [(Barcelona Supercomputing Center)](https://www.bsc.es/iserte-agut-sergio)) 

**Abstract:** The past few years have witnessed an increased support for programmable network adapters, known as "SmartNICs", which offer additional functionalities beyond standard packet processing capabilities. These devices often feature lightweight, programmable processing cores, FPGAs, and even CPU- and GPU-based platforms capable of running separate operating systems. Their primary target has been data center operations, such as infrastructure management, packet filtering, and I/O acceleration, but these devices are increasingly being explored for high-performance computing (HPC) application acceleration.

This tutorial offers an in-depth exploration of the state-of-the-art for SmartNICs and the emerging software ecosystems supporting them. Attendees will participate in hands-on exercises to better understand how to take advantage of SmartNICs for application acceleration, including MPI collective operation offloading, OpenMP offloading, system security, file I/O, and algorithmic modifications to maximize on-board processing power. Participants will have the opportunity to execute these exercises using cutting-edge SmartNICs such as NVIDIA's BlueField-3 Data Processing Unit (DPU). The presenters will discuss additional techniques for optimizing applications to harness SmartNICs as communication accelerators in HPC systems.


**Targeted Audience**: This tutorial is intended for HPC users, application developers, researchers and developers of programming models and communication libraries, as well as tool developers who are interested in leveraging next-generation SmartNICs for HPC applications. Hands-on interaction with an HPC cluster will be offered to all interested attendees.


>[!NOTE] 
> Please note that you must register for the ISC tutorial track and attend this tutorial in person.

[Register here](https://eu.avolio.swapcard.com/ISC/2025/registrations/Start)

## Agenda

| **Time (CET)** | **Topic**                                     | **Presenter** |
| -------------- | --------------------------------------------- | ------------- |
| 14:00 - 14:10  | Introduction and Attendee Survey              | Jeff          |
| 14:10 - 14:40  | SmartNIC introduction and overview            | Rich G        |
| 14:40 - 14:50  | Programming approaches for HPC with SmartNICs | Jeff          |
| 14:50 - 15:15  | SmartNIC Research – State of the Art          | Jeff          |
| 15:15 - 16:00  | DOCA MPI Implementations; Security Topics     | Rich G        |
| 16:00 - 16:30  | **Break**                                     |               |
| 16:30 - 17:10  | OpenMP offload to the SmartNIC; ODOS Demos    | Antonio       |
| 17:10 - 17:55  | Hands On - Application Experiences            | All           |
| 17:55 - 18:00  | Wrap-up                                       | All           |

## Hands-on Examples

Please see the examples under the `/code` folder. The tutorial slides will have additional details on running and interacting with each example.

See [this Google Doc](https://docs.google.com/document/d/1eRluI2IZ4iIY9jjAL53shEKqH0AqwEvPlwRCCJJ9Sec/edit?usp=sharing) for instructions on using GitHub authentication to access the testbed and start working with the examples!

## Slides

Slides will be posted under the slides folder the day of the event. 
