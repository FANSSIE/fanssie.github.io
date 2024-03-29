---
layout: default
---

*Framework for Antarctic System Science in E3SM (FAnSSIE)* is a climate and computational science project funded by the U.S. Department of Energy (DOE) to mature a capability for projecting the future of the Antarctic Ice Sheet within DOE's Energy Exascale Earth System Model (E3SM).

## Background

Sea-level rise (SLR) is a major impact of anthropogenic climate change, and future increases in sea level will lead to devastating impacts on coastal populations and infrastructure.    While the human, infrastructure, financial, and global security impacts of future SLR are immense, large uncertainty in projections complicate plans for mitigation and adaptation.   Despite more than a decade of effort and substantial improvements in ice-sheet models  future mass loss from the Antarctic Ice Sheet (AIS) remains the largest source of uncertainty in future SLR.   Because of the presence of tipping points and threshold processes in AIS evolution  and feedbacks between AIS and the larger climate system, future SLR is subject to "deep uncertainty".  Addressing this deep uncertainty  requires accurate incorporation of the known and hypothesized AIS tipping point processes into ice-sheet and Earth-system models, where they are currently poorly represented or completely absent.

![AIS deep uncertainty](images/AIS_uncertainty.png){: width="400" }

*Recent projections of the future contribution of the Antarctic Ice Sheet to sea-level rise, considering different assumptions about deep uncertainty ([projections with well-known processes](https://www.nature.com/articles/s41586-021-03302-y) in blue, [projections accounting for deep uncertainty in ice-shelf basal melt and hydrofracture](https://www.nature.com/articles/s41586-021-03302-y) in green, and [projections accounting for deep uncertainty due to Marine Ice Cliff Instability](https://www.nature.com/articles/s41586-021-03427-0) in orange.)*

## E3SM and Antarctic Science

The U.S. Department of Energy ([DOE](https://energy.gov/)) supports the [Energy Exascale Earth System Model (E3SM)](https://e3sm.org), a state-of-the-science Earth system model development and simulation project to investigate energy-relevant science using code optimized for DOE's advanced computers.  At the same time, DOE has invested in the development of advanced ice sheet models that place increased resolution in regions experiencing the largest and most rapid changes. The DOE-funded project *Framework for Antarctic System Science in E3SM (FAnSSIE)* builds on previous DOE investments to integrate and improve on these ice-sheet developments in the context of an Antarctic system fully integrated into the Earth system.  This project is supported by the DOE [Office of Science](https://www.energy.gov/science/office-science) program in [Scientific Discovery through Advanced Computing (SciDAC)](https://www.scidac.gov/), which is a partnership between the [Biological and Environmental Research (BER)](https://science.osti.gov/ber) [Earth and Environmental System Modeling (EESM) program](https://science.osti.gov/ber/Research/eessd/Earth-and-Environmental-System-Modeling) and [Advanced Scientific Computing Research (ASCR)](https://www.energy.gov/science/ascr/advanced-scientific-computing-research).

## FAnSSIE Goals

FAnSSIE creates an Antarctic system science capability for DOE’s E3SM climate model by adding key missing processes for the ice sheet, ocean, and snowpack, and the coupling between them.  These features include:
1. the ability of the ocean model to advance into previously ice-covered regions as the ice sheet retreats
2. the ability of the snowpack model to represent the formation and accumulation of meltwater in the snowpack, which can ultimately contribute to fracturing of the ice beneath
3. a representation of flowing ice that combines ductile and brittle behavior needed to simulate the formation of rifts and icebergs
4. the ability of the ice-sheet model mesh to align and evolve with rifts as they develop

These capabilities are supplemented by improvements to computational performance, more accurate representation of ice-sheet model physics, and a workflow for quantifying the uncertainty in sea-level change projections.  FAnSSIE builds on the development of the ice-sheet model MALI under the [ProSPect](https://doe-prospect.github.io/) SciDAC4 project.

FAnSSIE began in September 2022.  More information will be added as the project progresses.

![abumipMali](images/MALI-ABUMIP-200yrs.png)
*Antarctic ice sheet geometry and surface speed (color) 200 yrs after removal of all floating ice shelves (ABUMIP experiment) simulated by MALI.*

