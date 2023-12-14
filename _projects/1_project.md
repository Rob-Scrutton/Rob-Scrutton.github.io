---
layout: page
title: Detecting biomolecular self-assembly
description: Coupling CNNs with high-throughput microfluidics to efficiently probe biomolecular phase space
img: assets/img/phasescan_frame.png
importance: 1
category: work
related_publications: Qian2023.11.02.565376
---

Traditional pipetting experiments are great. They allow us to test out lots of different conditions for a given protein, and then we can see under what conditions certain phases are observed. Unfortunately, proteins are expensive and really hard to get in large quantities; as a physical chemist, the last thing I want to be doing (and likely failing to do) is expressing protein. So how can we explore the phase space of proteins whilst being conservative of sample? 

Microfluidics allows us to 'pipette' conditions on an extremely small scale, allowing us to save lots of protein sample. This means more data can be collected in phase space, or more experiments can be carried out after. <a href="https://www.nature.com/articles/s41467-022-35265-7" target="_blank">Arter et. al.</a> designed the first version of the setup. By flowing aqueous solutions perpendicular to an oil flow, picolitre water-in-oil droplets can be generated at a rapid rate (>1000/min). By varying the flow rates of input solutions, we can force each droplet to contain a slightly different condition. This allows us to generate a phase diagram for a protein with minimal sample (~20&mu;L).

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phasescan_frame.png" title="Microfluidic droplets containing biomolecules and different environmental conditions" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/phasescan_frame_nops.png" title="Microfluidic droplets containing biomolecules and different environmental conditions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Microfluidic droplets containing biomolecules under different environmental conditions. The images correspond to simultaneous imaging at two different wavelengths corresponding to two different components.
