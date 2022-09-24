# Developing and Executing Error-mitigated NISQ Algorithms across Devices and Simulators

## Presenters

This turorial was given by:

- Cristina Cirstoiu &rarr; <cristina.cirstoiu@quantinuum.com>
- Dan Mills &rarr; <daniel.mills@quantinuum.com>

## Abstract

In this tutorial, we will introduce tools and techniques for developing experiments and algorithms which use real quantum devices. The tutorial will start with designing quantum circuits, and integrating them in hybrid workflows with classical software. We’ll show how to use compilers to optimise and target circuits to devices and simulators, including strategies for combining compiler passes for specific applications. Worked examples from CQ’s TKET development kit will be used, as well as quantum software tools that integrate with TKET (e.g. Qiskit). Moving to executing circuits, we will first cover various kinds of simulation (statevector, stabilizer, unitary, symbolic, shot-based) to iterate and test the algorithm. Then we will move to best practices for running on real devices, including relative merits of devices, and designing the experiment to be portable across multiple device types (e.g. superconducting, ion-trap, cold atom). Taking a broad approach to minimising noise when executing on NISQ devices, the tutorial will also cover quantum error mitigation and the relative merits of state of the art error mitigation techniques, with worked examples from CQ’s Qermit error mitigation package. Combining the parts, we will move on to working through a real-world experiment.

## Documentation and Code Availability

Documentation for Qermit can be found at:
<p align=center><a href=https://qerm.it>qerm.it</a></p> 
and for TKET at: 
<p align=center><a href=https://cqcl.github.io/tket/pytket/api/index.html>https://cqcl.github.io/tket/pytket/api/index.html</a></p> 
The respective manuals can be found at: 

- <https://cqcl.github.io/Qermit/manual/> 
- <https://cqcl.github.io/pytket/manual/index.html> 

Both packages are open source and we welcome contributions or issues at the respective github repositories:

- <https://github.com/CQCL/Qermit> 
- <https://github.com/CQCL/tket>.

## Further Reading

The content of this tutorial complements research conducted at Quantinuum, including in particular:
- Volumetric Benchmarking of Error Mitigation with Qermit &rarr; <https://arxiv.org/abs/2204.09725>
- Spectral analysis for noise diagnostics and filter-based digital error mitigation &rarr; <https://arxiv.org/abs/2206.08811>