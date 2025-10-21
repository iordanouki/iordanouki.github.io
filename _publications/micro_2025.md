---
title: "Flexing RISC-V Instruction Subset Processors to Extreme Edge"
collection: publications
permalink: /publication/micro_2025
excerpt: ''
date: 17-10-2025
venue: 'IEEE/ACM International Symposium on Microarchitecture'
paperurl: 'https://dl.acm.org/doi/10.1145/3725843.3756036'
---

This paper presents an automated approach for designing processors that support a subset of the RISC-V instruction set architecture (ISA) for a new class of applications at Extreme Edge. The electronics used in extreme edge applications must be area and power-efficient, but also provide additional qualities, such as low cost, conformability, comfort and sustainability. Flexible electronics, rather than silicon-based electronics, will be able to meet the above qualities. For this purpose, we propose a methodology for generating RISC-V instruction subset processors (RISSPs) tailored to these applications and implementing them as flexible integrated circuits (FlexICs). The methodology makes verification an integral part of the processor design by treating each instruction in the ISA as a discrete, fully functional, pre-verified hardware block. It automatically builds a custom processor by stitching together the instruction hardware blocks required by an application or a set of applications in a specific domain. We generate RISSPs using the proposed methodology for three extreme edge applications, and embedded applications from the Embench benchmark suite. When synthesized, RISSPs can achieve 8-to-43% reduction in area and 3-to-30% reduction in power compared to a processor supporting the full RISC-V ISA, and are also on average ~40 times more energy efficient than Serv - the world’s smallest 32-bit RISC-V processor. When physically implemented as FlexICs, the three extreme edge RISSPs achieve up to 42% area and 21% power savings with respect to the full RISC-V processor.

[Find it on ACM Digital Library](https://dl.acm.org/doi/10.1145/3725843.3756036)
