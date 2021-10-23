---
title: "Analysis of the Usage Models of System Memory Management Unit in Accelerator-attached Translation Units."
collection: publications
permalink: /publication/memsys_2020
excerpt: ''
date: 28-09-2020
venue: 'MEMSYS 2020: The International Symposium on Memory Systems'
paperurl: 'https://dl.acm.org/doi/10.1145/3422575.3422781'
---
Including hardware accelerators to improve the performance while reducing energy consumption is becoming ubiquitous in computing systems ranging from large System-on-Chips (SoCs) for data centers to small embedded IoT devices. In accelerator-enabled environments, accelerator units are able to deliver a substantial increase in performance through increased programming effort and co-scheduling applications across the heterogeneous system. These accelerators need to have frequent access to the application data through the memory subsystem and therefore the need for efficient memory management is crucial. The memory subsystem needs to maintain the model of memory consistency between context switching, where resources such as accelerators are reallocated between applications and their defined memory space.

The consistency between the processor memory management and any System Memory Management Unit (SMMU) is either through the pinning of physical memory to specific virtual pages statically, or tracking page allocations dynamically and ensuring consistency at point of use of the memory between applications. Although the implication of these two methods has obvious consequences, the full implications on maintaining consistency of such translations have not been studied.

In this paper, we carry out use case measurements and analysis of three of the main usage models focused specifically on SoC level translation. We analyze the generic structure on SoCs given the example of the Zynq Ultrascale+ FPGA board that incorporates the state-of-the-art and widely used Arm System Memory Management Unit. We share our analysis and present the advantages and disadvantages to provide guidance in optimizing the integration of accelerators in a system. We also propose a usage model to utilize the embedded SMMU in order to enable accelerator devices to directly access application memory, through exposing a reusable API specific to the Zynq Ultrascale+ hardware.


[Download Preprint](https://www.research.manchester.ac.uk/portal/en/publications/analysis-of-the-usage-models-of-system-memory-management-unit-in-acceleratorattached-translation-units(cfc03054-c94c-4fd7-bdf9-3ad6c4641d1b).html)

[Find it on ACM Digital Library](https://dl.acm.org/doi/10.1145/3422575.3422781)
