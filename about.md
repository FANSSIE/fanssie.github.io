---
layout: page
title: About
permalink: /about/
---

*FAnSSIE* has three major foci: coupling of the Antarctic Ice Sheet (AIS) within E3SM, resolving ice-sheet instabilities in MALI, and probabilistic projections of the Antarctic Ice Sheet.


![FAnSSIE overview](/images/FAnSSIE-overview.png)


**Coupling of climate and Antarctic ice shelves within E3SM**

Projections of AIS evolution within E3SM are fundamentally precluded by the inability of the ocean component to adapt to the migration of the grounding line and calving front positions as ice shelves evolve. We will build on E3SM’s prototype “wetting and drying” capability to implement robust and general algorithms for advance and retreat of the ocean model boundary. Modifications to the E3SM coupler will support migration of the ice-shelf calving front in the ocean and land models. Additionally, we will improve the representation of atmospheric-driven melting in the snow and firn on the ice-sheet surface and add coupling between snowpack liquid-water content in E3SM' land model, ELM, and the ice-shelf stress state in MALI, as required to resolve hydrofracture and potential catastrophic failure of ice shelves. These developments are fundamental for E3SM to represent the tipping points associated with sub-shelf melt and hydrofracture.


**Resolving ice-sheet instabilities within MALI**

Accurate simulation of the ice-shelf damage, rifting, and calving front migration that contribute to Marine Ice Cliff Instability requires sophisticated representation of ice fracturing, advanced discretization methods, and high resolution. To accomplish this, we will introduce fracture mechanics methods that combine ductile flow and brittle failure in a single framework within MALI. To support the locally high resolution required for resolving MICI and MISI, we will implement unstructured mesh adaptivity combined with front capturing algorithms, leveraging FASTMath expertise. This will allow MALI’s mesh to align directly with the calving front, grounding line, and major fractures as they evolve in time and space, significantly improving accuracy without requiring sub-grid discretizations or overly-refined meshes. Mesh adaptivity together with improved discretization schemes for tracer advection will enable tighter integration of the velocity solver with other physics leading to higher accuracy at a lower computational cost. We will also introduce software modernization and performance improvements, through FASTMath and RAPIDS2 collaborations, to allow MALI to efficiently run on heterogeneous architectures and prepare E3SM for DOE exascale supercomputing platforms. These changes will provide key missing capabilities for MALI to efficiently and realistically represent the tipping points of Marine Ice Sheet Instability and Marine Ice Cliff Instability. 

**Probabilistic, climate-informed projections of the Antarctic Ice Sheet**

To generate probabilistic projections of the AIS contribution to future SLR that account for deep uncertainty, we will conduct ensembles of hundreds of AIS simulations that incorporate the four tipping point processes shown above. These large and computationally expensive ensembles will be enabled by the MALI performance improvements identified above. Further computational savings will be achieved by using lower-fidelity models, possibly including machine learning models, in a multi-fidelity uncertainty-quantification framework that builds on current FASTMath efforts. Improvements to MALI’s existing optimization tools through FASTMath collaborations will enable MALI initialization consistent with historical observations and applied climate forcing. Finally, sea-level rise uncertainty will be quantified through an integrated model toolchain from E3SM, through standalone MALI, to emulators.

